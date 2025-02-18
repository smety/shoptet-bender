# Shoptet Bender 🤖

## Introduction
Shoptet Bender proxies remote e-shop to localhost while injecting and serving your local `style.css` and `script.js`. This tool enables to development of visual changes without breaking the production e-shop. It is also suitable for Premium e-shop development, while emulation of the Blank mode is possible.

## How it works

```mermaid
graph TB
A(Customized e-shop) -- Browsersync proxy <br> and code injection --> B(Your browser)
C(Local files) -- Static served files --> B
```

## Install
Node v14 prerequisited\
Install global using yarn:\
`yarn global add git+https://github.com/shoptet/shoptet-bender.git`

## Usage
Try `shp-bender -h` for CLI help

## Posible tool improvements
Shoptet Bender is an open-source project, so your PRs are very welcomed. There are some suggestions for possible features, as Shoptet don't have the resources to develop this tool actively. So it is left as is for your active development. Some minor feature updates are possible.
What could be done:
- [ ] tools integration (Gulp, Grunt)
- [ ] files concatenation
- [ ] HEAD and BODY scripts location - this could better emulate admin fields