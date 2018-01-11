# Sass-color
Simple function for managing Sass colors

## Description
A SCSS function that accepts color values along with allowing the ability to set an opacity, and darken or lighten the color by a percentage value.

### Usage
Use this along with a SCSS color map and declare colors as needed throughout SCSS.

`color(color-name, $alpha: 1, $darken: 0, $lighten: 10%)`

By default, the `$alpha` is set to `1` but can be overridden and the `$darken` and `$lighten` are set to `0`.