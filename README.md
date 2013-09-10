responsive-grid
==========

A responsive grid system, written in Stylus, inspired by Bootstrap fluid grid.


## Install a default configured version

  Install with [component(1)](http://component.io):

    $ component install shallker/responsive-grid


## Quick Start
Get a copy of responsive-grid, import it and generate some semantice grids
```stylus
@import 'responsive-grid/stylus/index'

/* Default grid, for the browsers that don't support media query */
responsive-grid('desktop')

/* Tablet */
@media (max-width: 1020px)
  responsive-grid('tablet')

/* Mobile */
@media (max-width: 640px)
  responsive-grid('mobile')
```

Start using those grids in html
```html
<div class="row">
  <div class="desktop-3 tablet-6 mobile-12">
    <p>Section 1</p>
  </div>
  <div class="desktop-3 tablet-6 mobile-12">
    <p>Section 2</p>
  </div>
  <div class="desktop-3 tablet-6 mobile-12">
    <p>Section 3</p>
  </div>
  <div class="desktop-3 tablet-6 mobile-12">
    <p>Section 4</p>
  </div>
</div>
```


## Example
http://shallker.github.io/responsive-grid/test


## Todo


## License
MIT
