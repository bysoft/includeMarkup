### Include snippets of HTML into a page
Example script loading a separate file into a page

Steps
-----
1. include script
2. invoke function passing two arguments, file and container


Usage
-----

* include the script after loading jQuery

Code
----
    <script src=https://raw.github.com/bysoft/includeMarkup/master/js/core.js></script>

Execute
-------

* call function and specify the include file and selector statement of the wrapping element

Include Data
------------

    Drupal.dataInc('file.inc', '#wrap');
    