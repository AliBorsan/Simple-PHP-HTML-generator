# Simple-PHP-create-HTML-element-Class
This simple php class can create simple HTML elements also can create nested and complicated HTML elements.
It is an attempt to create an alternative of JavaScript createElement function buy using only PHP.
It is simple and flexable :
- You can use it to cretate unlimited single or nested elements.
- You can add your own _html() methods for defferent types of elements.
The class has three main methods:
- setAttributes(array $args):
  This methods collects the attributes from the object and prepare them to be used in its output.
- container_html($innerHTML = ''):
  This method construct the creation of an HTML container element.
  The method Fits for all opening and closing HTML tags and all none void elements like "div, p, header, footer, lists, tables, forms, ...etc" .
- input_html($innerHTML = ''):
      This method construct the creation of an HTML input element
    The method fits for all self-enclosing HTML tags and void elements like "img , input, br, hr, link ,  ...etc".
