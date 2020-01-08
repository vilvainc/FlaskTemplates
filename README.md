## Learning Flask Templates

**This Example code**
* This code demonstrates using basic templates (Jinja). 
* The function render_template() takes in all the arguments we pass to the templates for evaluation. 
* Handling of variables, conditions and looping is demonstrated.
* In addition it also separates html from the content to show how we can avoid code repetition. 

**What are Flask templates?**
Templates are files that contain static data as well as placeholders for dynamic data. A template is rendered with specific data to produce a final document. Flask uses the Jinja template library to render templates.

Special delimiters are used to distinguish Jinja syntax from the static data in the template. 
1. Anything between __{{  }}__ is an expression (variable substitution) that will be output to the final document. 
2. __{%  %}__ denotes a control flow statement like if and for. 

Unlike Python, blocks are denoted by start and end tags.

**Learn more**

* [Documentation](https://flask.palletsprojects.com/en/1.1.x/tutorial/templates/)
* [More Documentation](http://flask.palletsprojects.com/en/1.1.x/templating/)
* [Basic video](https://youtu.be/APh3jdVryF0)