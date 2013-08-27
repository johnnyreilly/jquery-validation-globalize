jQuery Validation Globalize
===========================

An extension to the jQuery Validation Plugin which makes it use Globalize for number and date parsing (enabling simple internationalized validation).

This extension has the following dependencies:
- jQuery
- jQuery Validation
- Globalize

##Getting started

Simply include jquery.validate.globalize.js on a page **after** jquery.validate.js and globalize.js.  Now you are validating using Globalize to do your number and date parsing.  Lucky you!

So what's different?  Well, for example, if you're catering for German users then you will be presumably using the "de-DE" Globalize culture.  If this culture has been selected at the time of validation then "Dienstag, 27. August 2013" will be successfully validated as a date and "10,5" will be successfully validated as a number.

The following validator methods are patched by jQuery Validation Globalize: 

- number
- min
- max
- range
- date

## Author
**John Reilly**

+ http://twitter.com/johnny_reilly

## Credits
Inspired by [Scott Hanselman's blog post](http://www.hanselman.com/blog/GlobalizationInternationalizationAndLocalizationInASPNETMVC3JavaScriptAndJQueryPart1.aspx) and evolved from [my blog post](http://icanmakethiswork.blogspot.com/2012/09/globalize-and-jquery-validate.html).  Entirely dependent upon [jQuery Validation](https://github.com/jzaefferer/jquery-validation) and [Globalize](https://github.com/jquery/globalize/).

## Copyright
Copyright © 2013 [John Reilly](mailto:johnny_reilly@hotmail.com).

##License

MIT license - [http://www.opensource.org/licenses/mit-license.php](http://www.opensource.org/licenses/mit-license.php)

##Changelog

###1.0.0 / 2013-08-27

- Initial release
