==========================
cmsplugin_syntax_highlight
==========================

cmsplugin_syntax_highlight add integration with SyntaxHighlighter at http://alexgorbatchev.com/SyntaxHighlighter/.  

Features:

- Use as an individual plugin or use in text plugins.
- Auto-discovered custom templates used to select formatting language and
  modeled after template handling in cmsplugin_gallery under
  https://github.com/centralniak/cmsplugin_gallery

Contributions and comments are welcome using Github at:
http://github.com/nmurrin/cmsplugin_syntax_highligh

cmsplugin_syntax_highlight requires SyntaxHighlighter available at
http://xgorbatchev.com/SyntaxHighlighter/.

Configuration
=============

#. Indicate the location of SyntaxHighlighter in your settings file with
   SYNTAX_HIGHLIGHTER = '/medial/syntaxhighlighter/'.  Indicate the actual
   location in your project.

#. There are simple templates included for the languages that I commonly use.
   If you need additional languages or just want to change the template then
   create a cmsplugin_syntax_highlight directory in your templates directory
   and add templates.  They will be 'discovered' by the plugin.

Bugs and Contribution
=====================

Please use Github to report bugs, feature requests and submit your code:
http://github.com/nmurrin/cmsplugin_syntax_highlight

:author: Norm Murrin
:date: 2013/05/08

