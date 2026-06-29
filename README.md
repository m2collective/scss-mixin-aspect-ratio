# SCSS Mixin Aspect Ratio

A package for integrating a mixin to create proportional blocks.

![npm](https://img.shields.io/npm/v/@m2collective/scss-mixin-aspect-ratio?style=for-the-badge)

___

## Installation

You can install the package automatically using NPM:

```
npm i @m2collective/scss-mixin-aspect-ratio
```

## Usage

To use the package, import it into your project:

```scss
@use "@m2collective/scss-mixin-aspect-ratio" as *;

.demo {
    @include aspect-ratio(1, 1) {
        //...
    };
}
```

## Changing the namespace

You can change the namespace during mixin import and use the mixin with a different namespace:

```scss
@use "@m2collective/scss-mixin-aspect-ratio" as mixin;

.demo {
    @include mixin.aspect-ratio(1, 1) {
        //...
    };
}
```

## License

The MIT License (MIT). Please see the [License file](LICENSE.txt) for more information.
