### Include snippets of HTML into a page
Example script loading a separate file into a page

Steps
-----
1. include script
2. invoke function passing two arguments, file and container


Usage
-----

* include the script after loading jQuery
    <script src=https://raw.github.com/bysoft/includeMarkup/master/js/core.js></script>

* call function and specify the include file and selector statement of the wrapping element
    Drupal.dataInc('file.inc', '#wrap');
    