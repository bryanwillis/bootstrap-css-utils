# Bootstrap CSS Utils

![Keep calm and add a class](keep-calm.png)

Bootstrap CSS Utils is collection of handy CSS helper classes you can use to complement [Bootstrap's own already amazing ones](http://getbootstrap.com/css/#helper-classes).


## Table of contents

* [Install](#install)
* [Rhythm classes](#rhythm-helper-classes)
* [Display classes](#display-helper-classes)

## Install

### Bower (coming soon!)

**Import the package**:  
```bash
bower install bootstrap-css-utils
```

**Include the CSS file**:  
```HTML
...
<head>
    <link href="bower_components/bootstrap-css-utils/dist/bootstrap-css-utils.min.css" rel="stylesheet" />
...
```


### Git

**Clone the repo**:  
```bash
git clone https://github.com/trumbitta/bootstrap-css-utils.git
```

**Copy the CSS file**:  
```
bootstrap-css-utils/dist/bootstrap-css-utils.min.css
```

**Or the non-minified version**:  
```
bootstrap-css-utils/dist/bootstrap-css-utils.css
```

**Include the CSS file**:  
```HTML
...
<head>
    <link href="bootstrap-css-utils.min.css" rel="stylesheet" />
...
```

## Rhythm helper classes

Vertical and Horizontal rhythm is very important in a good GUI. Whenever you are in need of a bit coherent spacing, use one of the *rhythm* classes

### Variations

Every class name is composed as follows: `[variant]-[direction]-[size]`

* **Variants:**
  * `margin`
  * `padding`
* **Directions:**
  * `vertical`
  * `horizontal`
* **Sizes:**
  * `xs`
  * `sm`
  * `md`
  * `lg`
  * `xl`

Size abbreviations have the same meaning as in Bootstrap, with the added `xl: extra-large` one.

### Examples

#### Medium vertical margin

```HTML
<!-- HTML -->

<div class="panel panel-default margin-vertical-md">
  ...
</div>
```

```CSS
/* CSS */

.margin-vertical-md {
  margin-top: 1em !important;
  margin-bottom: 1em !important;
}
```

#### Large horizontal padding

```HTML
<!-- HTML -->

<div class="padding-horizontal-lg">
  ...
</div>
```

```CSS
/* CSS */

.padding-horizontal-lg {
  padding-left: 2em !important;
  padding-right: 2em !important;
}
```

## Display helper classes

When you are dealing with complex CSS shenanigans and need some quick little touches of display wizardry, use one of these:

```CSS
.display-inline {
  display: inline !important;
}

.display-block {
  display: block !important;
}

.display-inline-block {
  display: inline-block !important;
}
```
