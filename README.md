o-markitdigital-test
=================

This is a test Origami component created by Markit Digital for POC purposes.

- [Usage](#usage)
	- [Markup](#markup)
	- [JavaScript](#javascript)
- [Contact](#contact)
- [Licence](#licence)

## Usage

_Whatever usage instructions your component has. We've broken this down by Markup, JavaScript and Sass, but it depends how complex your component is._

### Markup

_Common templating can go here, especially if there is only one template, but people can always check the demos for more._

_Remember to start your codeblocks with three backticks and "html" so your markup is syntax highlighted correctly._

```html
<div data-o-component="o-markitdigital-test" class='o-markitdigital-test'>
</div>
```

### JavaScript
No code will run automatically unless you are using the Build Service.
You must either construct an `o-markitdigital-test` object or fire the `o.DOMContentLoaded` event, which oComponent listens for.

#### Constructing an o-markitdigital-test

```js
const oMarkitDigitalTest = require('o-markitdigital-test');

const oMarkitDigitalTest = new oMarkitDigitalTest();
```

#### Firing an oDomContentLoaded event

```js
document.addEventListener('DOMContentLoaded', function() {
	document.dispatchEvent(new CustomEvent('o.DOMContentLoaded'));
});
```

### Sass

## Contact

----

## Licence
This software is published by Markit Digital under the [MIT licence](http://opensource.org/licenses/MIT).