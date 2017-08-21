# bootstrap3-breakpoints
Bootstrap 3 breakpoints, inspired by Bootstrap 4

# Available Variables
These are available variables from Bootstrap 3.x
- ```$screen-xs-min```: 480px
- ```$screen-sm-min```:              768px;
- ```$screen-md-min```:                  992px;
- ```$screen-lg-min```:                  1200px;

- ```$screen-xs-max```: 767px;
- ```$screen-sm-max```: 991px;
- ```$screen-md-max```: 1199px;

# Available Breakpoints
Apply styles for devices with maximum width up to ```$size```
```
@mixin media-breakpoint-up($size)
```
Apply styles for devices with minimum width of ```$size```
```
@mixin media-breakpoint-down($size)
```
Apply styles for devices up with width between ```$small``` and ```$large```
```
@mixin media-breakpoint-between($small, $large)
```

# Usage
Using the variables (above), you can use the mixin functions like below:
```
@include media-breakpoint-up($screen-sm-min) { ... }
```
