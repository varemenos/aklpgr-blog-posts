# Dropplets template variables and fuctions
- Adonis K.
- varemenos
- 2013/09/27
- Dropplets
- published

It seems like there is no documentation for Dropplets' templates, so I did some digging and found the variables and functions that can be used for template development.

__variables__:

* all_posts
* blog\_email
* blog\_image
* blog\_title
* blog\_twitter
* blog\_url
* cache\_directory
* cachefile
* category
* content
* currentpage
* date\_format
* dropplets
* error\_text
* error\_title
* feed\_max\_items
* filename
* footer\_inject
* get\_page\_meta
* hasher
* header\_inject
* homepage
* image
* index\_cache
* index\_file
* infinite\_scroll
* intro\_text
* intro\_title
* is\_home
* language
* meta\_description
* not\_found\_file
* offset
* page
* page\_meta
* page\_title
* pagination
* pagination\_on\_off
* password
* php\_errormsg
* plugin
* post
* post\_author
* post\_author\_twitter
* post\_cache
* post\_category
* post\_category\_link
* post\_content
* post\_directory
* post\_file
* post\_image
* post\_intro
* post\_link
* post\_status
* post\_title
* posts
* posts\_dir
* posts\_file
* posts\_per\_page
* published\_date
* published\_iso\_date
* template
* template\_dir
* template\_dir\_url

__functions__:

* count\_premium\_templates
* get\_all\_posts
* get\_footer
* get\_header
* get\_installed\_templates
* get\_pagination
* get\_posts\_for\_category
* get\_premium\_templates
* get\_twitter\_profile\_img
* identify\_modifier\_markdown
* markdown
* smarty\_modifier\_markdown

> Those are the vars and functions returned via `get_defined_vars()` and `get_defined_functions()`
