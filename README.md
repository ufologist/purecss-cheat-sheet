# purecss-cheat-sheet@`0.6.2`

[Pure.css](https://github.com/yahoo/pure/) Cheat Sheet.

> A set of small, responsive CSS modules that you can use in every web project. The entire set of modules clocks in at *3.8KB* minified and gzipped.

## Base

> In addition to [Normalize.css](https://necolas.github.io/normalize.css/) rules, Pure's Base module contains some common styles that are used by most websites.

* `[hidden]`
* `img.pure-img`


## Grids

> Pure Grids consist of two types of classes: the grid class (`pure-g`) and unit classes (`pure-u` or `pure-u-*`). For example, `pure-u-1-2` has a width of 50%, whereas `pure-u-1-5` would have a width of 20%.

> Pure ships with both a **5ths** and **24ths** based grid.

> Since media queries cannot be over-written, we **do not** include the grid system as part of pure.css. You'll have to pull it in as a separate CSS file.
> 
> `<link rel="stylesheet" href="https://unpkg.com/purecss@0.6.2/build/grids-responsive-min.css">`

* `.pure-g`
  * `.pure-u-*`
  * `.pure-u-sm-*`
  * `.pure-u-md-*`
  * `.pure-u-lg-*`
  * `.pure-u-xl-*`

## Menus

> Menus are vertical by default. Menu items take up 100% of the width of their container, so you may want to limit the menu width or set the menu to `display:inline-block`.

用作菜单或者导航

* `.pure-menu.pure-menu-horizontal.pure-menu-scrollable.pure-menu-fixed`
  * `.pure-menu-heading`
  * `ul.pure-menu-list`
    * `li.pure-menu-item.pure-menu-selected.pure-menu-disabled.pure-menu-has-children.pure-menu-allow-hover`
      * `a.pure-menu-link`
      * `ul.pure-menu-children`
        * `li.pure-menu-item`
    * `li.pure-menu-separator`

## Buttons

> To create a Pure Button, add the `pure-button` classname to any `<a>` or `<button>` element.

* `.pure-button-group`
  * `.pure-button.pure-button-primary.pure-button-active.pure-button-disabled`

## Forms

> To create a default inline form, add the `pure-form` classname to any `<form>` element.

* `form.pure-form.pure-form-stacked`
  * `.pure-form-message.pure-form-message-inline`
  * `.pure-checkbox`
  * `.pure-radio`
  * `.pure-input-rounded`

### Aligned Form

* `form.pure-form.pure-form-aligned`
  * `.pure-control-group`
  * `.pure-controls`

### Grouped Inputs

* `.form.pure-form`
  * `fieldset.pure-group`
    * `.pure-input-1-2`

## Tables

> To style an HTML table, add the `pure-table` classname.

* `table.pure-table.pure-table-horizontal.pure-table-bordered`
