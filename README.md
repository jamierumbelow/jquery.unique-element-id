jquery.unique-element-id.js
===========================

This is a very simple jQuery plugin that generates a totally unique ID for an element. This is useful if you're working with a variable number of elements on a page and need to differentiate between them programatically. I used it recently to keep track of a large number of **setTimeout** timers, for instance.

Include the file in your page:

```html
<script type="text/javascript" src="/javascripts/jquery.unique-element-id.js"></script>
```
	
And then call the `.uid()` method to generate a unique ID:

```javascript
console.log( "The .some_element_selector UID is: " + $('.some_element_selector').uid() );
console.log( "The .other_element_selector UID is: " + $('.other_element_selector').uid() );
```

This plugin is [licensed under the MIT license](http://www.opensource.org/licenses/MIT), which means you can do absolutely anything you want with it, assuming you keep the copyright notices intact. Enjoy!