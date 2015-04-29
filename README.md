# shared

The `shared` module contains high-level rule-sets which apply a consistent,
shared declaration across a number of elements.

## Dependencies

The `shared` module depends on one other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the `shared` module using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Instalation

You can install the `shared` module via Bower, npm, or copy and paste.

## Install using Bower:

```sh
$ bower install tree-shared --save
```

Once installed, `@import` into your project in its Generic layer:

```scss
@import "bower_components/tree-shared/generic.shared";
```

## Install using npm:

```sh
$ npm install tree-shared --save
```

### Install via file download

The least recommended option for installation is to simply download
`_generic.shared.scss` into your project and `@import` it into your project 
in its Generic layer.

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
