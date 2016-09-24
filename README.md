# currency-flag-css

A collection of all currency flags in SVG — plus the CSS for easier integration.

inspired by: [lipis/flag-icon-css][https://github.com/lipis/flag-icon-css]

Install
-------
You can either [download](https://github.com/lipis/flag-icon-css) the whole project.

## Usage

For using the flags inline with text add the classes `.flag-icon` and
`.flag-icon-xxxx` (where `xxxx` is the
[ISO?? currency code](http://www.iso.org/iso/country_names_and_code_elements)
of a currency) to an empty `<span>`. If you want to have a squared version flag
then add the class `flag-icon-squared` as well. Example:

```html
<span class="flag-icon flag-icon-gr"></span>
<span class="flag-icon flag-icon-gr flag-icon-squared"></span>
```

You could also apply this to any element, but in that case you'll have to use the
`flag-icon-background` instead of `flag-icon` and you're set. This will add the
correct background with the following CSS properties:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Which means that the flag is just going to appear in the middle of an element, so
you will have to set manually the correct size of 4 by 3 ratio or if it's squared
add also the `flag-icon-squared` class.
