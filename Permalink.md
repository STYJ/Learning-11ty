---
# permalink: "this-is-a-new-path/subdirectory/testing/"         # this will write to _site/this-is-a-new-path/subdirectory/testing/index.html

# mySlug: this-is-a-new-path                                    # this will write to _site/subdir/this-is-a-new-path/index.html
# permalink: "subdir/{{ mySlug }}/index.html"                   # this will write to _site/subdir/this-is-a-new-path/index.html

# permalink: "{{ page.filePathStem }}.html"                     # this will write to _site/Permalink.html instead of the normal _site/Permalink/index.html. "page" is the data supplied automatically by 11ty, you can read more it here https://www.11ty.dev/docs/data-eleventy-supplied/. Also make sure you use quotes when referencing variables with {{  }} or YAML might parse this as an object

# title: My Article Title                                       # Use the provided slug filter to modify other data available in the template. 
# permalink: "subdir/{{ title | slug }}/index.html"             # This will write to _site/subdir/my-article-title/index.html.

# date: "2016-01-01T06:00-06:00"                                # this will write to _site/2016/01/01/index.html
# permalink: "/{{ page.date | date: '%Y/%m/%d' }}/index.html"   # this will write to _site/2016/01/01/index.html

---

# learning about permalinks

https://www.11ty.dev/docs/permalinks/