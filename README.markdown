Render a block from any template.
=================================

This is from [Snippet 942](http://djangosnippets.org/snippets/942/)
Which in turn was adapted from [769](http://djangosnippets.org/snippets/769/)

Changes I've made:
------------------

1. Reformat code style to [PEP-8](http://www.python.org/dev/peps/pep-0008/) (in progress; I'm learning).
2. Fix problem with nested `{% extends %}` in django 1.3+, as per [this comment](http://djangosnippets.org/snippets/942/#c3466) on the 942 snippet.
3. Refactor `_render_template_block_nodelist` for neater handling of exceptions (todo)

The description in [snippet 769](http://djangosnippets.org/snippets/769/) has some usage examples, and this [StackOverflow thread](http://stackoverflow.com/questions/882215/rendering-json-objects-using-a-django-template-after-an-ajax-call) also provides an example.
