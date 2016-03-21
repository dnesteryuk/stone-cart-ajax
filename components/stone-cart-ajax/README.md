# Stone cart ajax

It is a [Polymer-based](https://www.polymer-project.org) element for storing the shopping cart built on top of the [stone-cart](/dnesteryuk/stone-cart) element.

The documentation can be found [here](http://dnesteryuk.github.io/stone-cart/).

## Install

```
$ bower install stone-cart-ajax --save
```

## Usage

Add polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
```

Import custom element:

```html
<link rel="import" href="bower_components/stone-cart-ajax/stone-cart-ajax.html">
```

## Development

Install dependencies:

```
$ npm install -g bower polyserve
$ bower install
```

Launch [Polyserve](https://github.com/polymerlabs/polyserve):

```
$ polyserve
```

### Testing

Install:

```
$ npm install -g web-component-tester
```

Run tests:

```
$ wct
```

### Update GitHub pages

Install dependencies:

```
$ npm install -g yo generator-polymer
```

Pull changes:

```
$ yo polymer:gh
```

## License

[MIT License](https://opensource.org/licenses/MIT)
