# Bootstrap-4-utilities

Bootstrap 4 utility classes for Bootstrap 3 or any other project in LESS and CSS. These are very useful helper classes including common as well as responsive float, spacing and text-align classes which you can easily include in any of your project.

## Installation

Just download the project and include the CSS file in your project. Nothing fancy here! You can also include the LESS files in your project and add your own custom utility classes on top of it.

## Usage

Include the stylesheet on your document's `<head>`

```html
<head>
  <link rel="stylesheet" href="bootstrap-4-utilities.min.css">
</head>
```

Next, start adding the classes as and when required.

The utility classes are categorized as `Float`, `Text Align` and `Spacing` and each category is divided into two sections - `Common` and `Responsive`.

For responsive utility classes, the breakpoints are considered same as in Bootstrap 3 which are the following:
* `xs (<768px)` (This breakpoint abbreviation is not used in the classes as it applies to all the breakpoints from xs to xl)
* `sm (≥768px)`
* `md (≥992px)`
* `lg (≥1200px)`

Please find the details of the available classes below.

## Float

Toggle floats on any element, across any breakpoint, using responsive float utilities.

#### Common Float Classes Examples:

```html
<div class="float-left">Float left on all viewport sizes</div>
<div class="float-right">Float right on all viewport sizes</div>
<div class="float-none">Don't float on all viewport sizes</div>
```

#### Responsive Float Classes Examples:

```html
<div class="float-sm-left">Float left on viewports sized SM (small) or wider</div>
<div class="float-md-left">Float left on viewports sized MD (medium) or wider</div>
<div class="float-lg-left">Float left on viewports sized LG (large) or wider</div>
<div class="float-sm-right float-lg-left">Float right on viewports sized SM to MD. Float left on viewports sized LG or wider</div>
```

All available float classes:

* `.float-left`
* `.float-right`
* `.float-none`
* `.float-sm-left`
* `.float-sm-right`
* `.float-sm-none`
* `.float-md-left`
* `.float-md-right`
* `.float-md-none`
* `.float-lg-left`
* `.float-lg-right`
* `.float-lg-none`


## Text Alignment

Easily align text to left, right or center, across any breakpoint, with text alignment classes.

#### Common Text Alignment Classes Examples:

```html
<p class="text-left">Left aligned text on all viewport sizes.</p>
<p class="text-center">Center aligned text on all viewport sizes.</p>
<p class="text-right">Right aligned text on all viewport sizes.</p>
```

#### Responsive Text Alignment Classes Examples:

```html
<p class="text-sm-left">Left aligned text on viewports sized SM (small) or wider.</p>
<p class="text-md-left">Left aligned text on viewports sized MD (medium) or wider.</p>
<p class="text-lg-left">Left aligned text on viewports sized LG (large) or wider.</p>
<p class="text-sm-right text-lg-left">Right aligned text on viewports sized SM to MD. Left aligned text on viewports sized LG or wider</p>
```

All available text alignment classes:

* `.text-left`
* `.text-right`
* `.text-center`
* `.text-sm-left`
* `.text-sm-right`
* `.text-sm-center`
* `.text-md-left`
* `.text-md-right`
* `.text-md-center`
* `.text-lg-left`
* `.text-lg-right`
* `.text-lg-center`


## Spacing

Assign responsive-friendly margin or padding values to an element or a subset of its sides with shorthand classes. Includes support for individual properties, all properties, and vertical and horizontal properties. 

#### Notation:
The classes are named using the format `{property}{sides}-{size}` for `xs`, i.e., across all breakpoints and `{property}{sides}-{breakpoint}-{size}` for `sm(≥768px)`, `md(≥992px)`, and `lg(≥1200px)`.

Where property is one of:

* `m` - for classes that set `margin`
* `p` - for classes that set `padding`


Where sides is one of:

* `t` - for classes that set `margin-top` or `padding-top`
* `b` - for classes that set `margin-bottom` or `padding-bottom`
* `l` - for classes that set `margin-left` or `padding-left`
* `r` - for classes that set `margin-right` or `padding-right`
* `x` - for classes that set both `*-left` and `*-right`
* `y` - for classes that set both `*-top` and `*-bottom`
* blank - for classes that set a `margin` or `padding` on all 4 sides of the element


Where size is one of:

* `0` - for classes that eliminate the `margin` or `padding` by setting it to 0
* `1` - (by default) for classes that set the `margin` or `padding` to .25rem
* `2` - (by default) for classes that set the `margin` or `padding` to .5rem
* `3` - (by default) for classes that set the `margin` or `padding` to 1rem
* `4` - (by default) for classes that set the `margin` or `padding` to 1.5rem
* `5` - (by default) for classes that set the `margin` or `padding` to 3rem
* `auto` - for classes that set the `margin` to auto


#### Common Spacing Classes Examples:

```html
<div class="mt-0">Margin top 0 on all viewport sizes</div>
<div class="ml-1">Margin left .25rem on all viewport sizes</div>
<div class="px-2">Padding left and right .5rem on all viewport sizes</div>
<div class="p-3">Padding 1rem on all sides across all viewport sizes</div>
```

#### Responsive Spacing Classes Examples:

```html
<div class="mt-sm-0">Margin top 0 on viewports sized SM (small) or wider</div>
<div class="my-md-1">Margin top and bottom .25rem on viewports sized MD (medium) or wider</div>
<div class="p-lg-4">Padding 1.5rem on all sides on viewports sized LG (large) or wider</div>
<div class="mt-sm-1 mt-lg-3">Margin top .25rem on viewports sized SM to MD. Margin top 1rem on viewports sized LG or wider</div>
```

All available spacing classes:

_**Margin**_

`xs and above` | `sm and above` | `md and above` | `lg and above`
------------ | ------------- | ------------- | -------------
`.m-0` | `.m-sm-0` | `.m-md-0` | `.m-lg-0` 
`.mt-0` | `.mt-sm-0` | `.mt-md-0` | `.mt-lg-0` 
`.mr-0` | `.mr-sm-0` | `.mr-md-0` | `.mr-lg-0` 
`.mb-0` | `.mb-sm-0` | `.mb-md-0` | `.mb-lg-0` 
`.ml-0` | `.ml-sm-0` | `.ml-md-0` | `.ml-lg-0` 
`.mx-0` | `.mx-sm-0` | `.mx-md-0` | `.mx-lg-0` 
`.my-0` | `.my-sm-0` | `.my-md-0` | `.my-lg-0` 
`.m-1` | `.m-sm-1` | `.m-md-1` | `.m-lg-1` 
`.mt-1` | `.mt-sm-1` | `.mt-md-1` | `.mt-lg-1` 
`.mr-1` | `.mr-sm-1` | `.mr-md-1` | `.mr-lg-1` 
`.mb-1` | `.mb-sm-1` | `.mb-md-1` | `.mb-lg-1` 
`.ml-1` | `.ml-sm-1` | `.ml-md-1` | `.ml-lg-1` 
`.mx-1` | `.mx-sm-1` | `.mx-md-1` | `.mx-lg-1` 
`.my-1` | `.my-sm-1` | `.my-md-1` | `.my-lg-1` 
`.m-2` | `.m-sm-2` | `.m-md-2` | `.m-lg-2` 
`.mt-2` | `.mt-sm-2` | `.mt-md-2` | `.mt-lg-2` 
`.mr-2` | `.mr-sm-2` | `.mr-md-2` | `.mr-lg-2` 
`.mb-2` | `.mb-sm-2` | `.mb-md-2` | `.mb-lg-2` 
`.ml-2` | `.ml-sm-2` | `.ml-md-2` | `.ml-lg-2` 
`.mx-2` | `.mx-sm-2` | `.mx-md-2` | `.mx-lg-2` 
`.my-2` | `.my-sm-2` | `.my-md-2` | `.my-lg-2` 
`.m-3` | `.m-sm-3` | `.m-md-3` | `.m-lg-3` 
`.mt-3` | `.mt-sm-3` | `.mt-md-3` | `.mt-lg-3` 
`.mr-3` | `.mr-sm-3` | `.mr-md-3` | `.mr-lg-3` 
`.mb-3` | `.mb-sm-3` | `.mb-md-3` | `.mb-lg-3` 
`.ml-3` | `.ml-sm-3` | `.ml-md-3` | `.ml-lg-3` 
`.mx-3` | `.mx-sm-3` | `.mx-md-3` | `.mx-lg-3` 
`.my-3` | `.my-sm-3` | `.my-md-3` | `.my-lg-3` 
`.m-4` | `.m-sm-4` | `.m-md-4` | `.m-lg-4` 
`.mt-4` | `.mt-sm-4` | `.mt-md-4` | `.mt-lg-4` 
`.mr-4` | `.mr-sm-4` | `.mr-md-4` | `.mr-lg-4` 
`.mb-4` | `.mb-sm-4` | `.mb-md-4` | `.mb-lg-4` 
`.ml-4` | `.ml-sm-4` | `.ml-md-4` | `.ml-lg-4` 
`.mx-4` | `.mx-sm-4` | `.mx-md-4` | `.mx-lg-4` 
`.my-4` | `.my-sm-4` | `.my-md-4` | `.my-lg-4` 
`.m-5` | `.m-sm-5` | `.m-md-5` | `.m-lg-5` 
`.mt-5` | `.mt-sm-5` | `.mt-md-5` | `.mt-lg-5` 
`.mr-5` | `.mr-sm-5` | `.mr-md-5` | `.mr-lg-5` 
`.mb-5` | `.mb-sm-5` | `.mb-md-5` | `.mb-lg-5` 
`.ml-5` | `.ml-sm-5` | `.ml-md-5` | `.ml-lg-5` 
`.mx-5` | `.mx-sm-5` | `.mx-md-5` | `.mx-lg-5` 
`.my-5` | `.my-sm-5` | `.my-md-5` | `.my-lg-5`  
`.m-auto` | `.m-sm-auto` | `.m-md-auto` | `.m-lg-auto` 
`.mt-auto` | `.mt-sm-auto` | `.mt-md-auto` | `.mt-lg-auto` 
`.mr-auto` | `.mr-sm-auto` | `.mr-md-auto` | `.mr-lg-auto` 
`.mb-auto` | `.mb-sm-auto` | `.mb-md-auto` | `.mb-lg-auto` 
`.ml-auto` | `.ml-sm-auto` | `.ml-md-auto` | `.ml-lg-auto` 
`.mx-auto` | `.mx-sm-auto` | `.mx-md-auto` | `.mx-lg-auto` 
`.my-auto` | `.my-sm-auto` | `.my-md-auto` | `.my-lg-auto`  


_**Padding**_

`xs and above` | `sm and above` | `md and above` | `lg and above`
------------ | ------------- | ------------- | -------------
`.p-0` | `.p-sm-0` | `.p-md-0` | `.p-lg-0` 
`.pt-0` | `.pt-sm-0` | `.pt-md-0` | `.pt-lg-0` 
`.pr-0` | `.pr-sm-0` | `.pr-md-0` | `.pr-lg-0` 
`.pb-0` | `.pb-sm-0` | `.pb-md-0` | `.pb-lg-0` 
`.pl-0` | `.pl-sm-0` | `.pl-md-0` | `.pl-lg-0` 
`.px-0` | `.px-sm-0` | `.px-md-0` | `.px-lg-0` 
`.py-0` | `.py-sm-0` | `.py-md-0` | `.py-lg-0` 
`.p-1` | `.p-sm-1` | `.p-md-1` | `.p-lg-1` 
`.pt-1` | `.pt-sm-1` | `.pt-md-1` | `.pt-lg-1` 
`.pr-1` | `.pr-sm-1` | `.pr-md-1` | `.pr-lg-1` 
`.pb-1` | `.pb-sm-1` | `.pb-md-1` | `.pb-lg-1` 
`.pl-1` | `.pl-sm-1` | `.pl-md-1` | `.pl-lg-1` 
`.px-1` | `.px-sm-1` | `.px-md-1` | `.px-lg-1` 
`.py-1` | `.py-sm-1` | `.py-md-1` | `.py-lg-1` 
`.p-2` | `.p-sm-2` | `.p-md-2` | `.p-lg-2` 
`.pt-2` | `.pt-sm-2` | `.pt-md-2` | `.pt-lg-2` 
`.pr-2` | `.pr-sm-2` | `.pr-md-2` | `.pr-lg-2` 
`.pb-2` | `.pb-sm-2` | `.pb-md-2` | `.pb-lg-2` 
`.pl-2` | `.pl-sm-2` | `.pl-md-2` | `.pl-lg-2` 
`.px-2` | `.px-sm-2` | `.px-md-2` | `.px-lg-2` 
`.py-2` | `.py-sm-2` | `.py-md-2` | `.py-lg-2` 
`.p-3` | `.p-sm-3` | `.p-md-3` | `.p-lg-3` 
`.pt-3` | `.pt-sm-3` | `.pt-md-3` | `.pt-lg-3` 
`.pr-3` | `.pr-sm-3` | `.pr-md-3` | `.pr-lg-3` 
`.pb-3` | `.pb-sm-3` | `.pb-md-3` | `.pb-lg-3` 
`.pl-3` | `.pl-sm-3` | `.pl-md-3` | `.pl-lg-3` 
`.px-3` | `.px-sm-3` | `.px-md-3` | `.px-lg-3` 
`.py-3` | `.py-sm-3` | `.py-md-3` | `.py-lg-3` 
`.p-4` | `.p-sm-4` | `.p-md-4` | `.p-lg-4` 
`.pt-4` | `.pt-sm-4` | `.pt-md-4` | `.pt-lg-4` 
`.pr-4` | `.pr-sm-4` | `.pr-md-4` | `.pr-lg-4` 
`.pb-4` | `.pb-sm-4` | `.pb-md-4` | `.pb-lg-4` 
`.pl-4` | `.pl-sm-4` | `.pl-md-4` | `.pl-lg-4` 
`.px-4` | `.px-sm-4` | `.px-md-4` | `.px-lg-4` 
`.py-4` | `.py-sm-4` | `.py-md-4` | `.py-lg-4` 
`.p-5` | `.p-sm-5` | `.p-md-5` | `.p-lg-5` 
`.pt-5` | `.pt-sm-5` | `.pt-md-5` | `.pt-lg-5` 
`.pr-5` | `.pr-sm-5` | `.pr-md-5` | `.pr-lg-5` 
`.pb-5` | `.pb-sm-5` | `.pb-md-5` | `.pb-lg-5` 
`.pl-5` | `.pl-sm-5` | `.pl-md-5` | `.pl-lg-5` 
`.px-5` | `.px-sm-5` | `.px-md-5` | `.px-lg-5` 
`.py-5` | `.py-sm-5` | `.py-md-5` | `.py-lg-5` 


Since these are available in Bootstrap 4, most of the content above is taken from Bootstrap 4 docs. You can also checkout the links below for more info:

* `Float` - (https://getbootstrap.com/docs/4.0/utilities/float/)
* `Text Align` - (https://getbootstrap.com/docs/4.0/utilities/text/#text-alignment)
* `Spacing` - (https://getbootstrap.com/docs/4.0/utilities/spacing/)

Please note the breakpoints in these classes are different from what is mentioned in the links above as these classes are modified to be used in Bootstrap 3 projects.

## License

This project is licensed under the MIT License (http://opensource.org/licenses/MIT).
