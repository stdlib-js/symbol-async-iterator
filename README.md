<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Async Iterator Symbol

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Async iterator [symbol][mdn-symbol] which specifies the default async iterator for an object.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/symbol-async-iterator
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm` branch][esm-url].
-   If you are using Deno, visit the [`deno` branch][deno-url].
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd` branch][umd-url].

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

</section>

<section class="usage">

## Usage

```javascript
var AsyncIteratorSymbol = require( '@stdlib/symbol-async-iterator' );
```

#### AsyncIteratorSymbol

Async iterator [`symbol`][mdn-symbol] which specifies the default async iterator for an object.

```javascript
var s = typeof AsyncIteratorSymbol;
// e.g., returns 'symbol'
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

## Notes

-   The [symbol][mdn-symbol] is only supported in environments which support [symbols][mdn-symbol] and async iterators. In non-supporting environments, the value is `null`.

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var AsyncIteratorSymbol = require( '@stdlib/symbol-async-iterator' );

if ( AsyncIteratorSymbol === null ) {
    console.log( 'Environment does not support Symbol.asyncIterator.' );
} else {
    console.log( 'Environment does support Symbol.asyncIterator.' );
}
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/symbol/ctor`][@stdlib/symbol/ctor]</span><span class="delimiter">: </span><span class="description">symbols.</span>
-   <span class="package-name">[`@stdlib/symbol/iterator`][@stdlib/symbol/iterator]</span><span class="delimiter">: </span><span class="description">symbol iterator.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/symbol-async-iterator.svg
[npm-url]: https://npmjs.org/package/@stdlib/symbol-async-iterator

[test-image]: https://github.com/stdlib-js/symbol-async-iterator/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/symbol-async-iterator/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/symbol-async-iterator/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/symbol-async-iterator?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/symbol-async-iterator.svg
[dependencies-url]: https://david-dm.org/stdlib-js/symbol-async-iterator/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/symbol-async-iterator/tree/deno
[umd-url]: https://github.com/stdlib-js/symbol-async-iterator/tree/umd
[esm-url]: https://github.com/stdlib-js/symbol-async-iterator/tree/esm
[branches-url]: https://github.com/stdlib-js/symbol-async-iterator/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/symbol-async-iterator/main/LICENSE

[mdn-symbol]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol

<!-- <related-links> -->

[@stdlib/symbol/ctor]: https://github.com/stdlib-js/symbol-ctor

[@stdlib/symbol/iterator]: https://github.com/stdlib-js/symbol-iterator

<!-- </related-links> -->

</section>

<!-- /.links -->
