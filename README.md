# Analytics Dashboard

This project is using [Ruby](https://www.ruby-lang.org/en/) to build a high powered analytics dashboard website using [Google Charts](https://developers.google.com/chart/) [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) library which is being hosted on [GitHub Pages](https://pages.github.com/) at https://rubylightsaber.github.io/dashboard/.

This project was originally based on a real commercial software project and it builds statistics by [data mining](https://en.wikipedia.org/wiki/Data_mining) [XML Schema](https://www.w3.org/XML/Schema) from a software system.  Most of the XML Schema for this project was hand created and the rest comes from the open source Ruby programming language.

Another interesting technique that is being used is [concatenation](https://en.wikipedia.org/wiki/Concatenation) to build all the [HTML 5](https://developer.mozilla.org/en-US/docs/Web/HTML) pages, which are then written to files via [variable interpolation](http://batsov.com/articles/2014/08/13/the-elements-of-style-in-ruby-number-14-variable-interpolation/).

[Bootstrap](http://getbootstrap.com/) and [jQuery](https://jquery.com/) are being used for a [responsive designed](https://responsivedesign.is/) mobile first website.

Ruby instance variables are being used for each HTML page via the [instance_variable_get](http://apidock.com/ruby/Object/instance_variable_get) and [instance_variable_set](http://apidock.com/ruby/Object/instance_variable_set) built in Ruby custom functions.  

[Ruby global variables](https://www.tutorialspoint.com/ruby/ruby_variables.htm) are being used for the width and height of each chart.


# Contributions

Fork and pull request. Simple.
