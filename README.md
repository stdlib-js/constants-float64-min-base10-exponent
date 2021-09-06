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

# Minimum Base 10 Exponent

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] [![dependencies][dependencies-image]][dependencies-url]

> The minimum base 10 exponent for a normal [double-precision floating-point number][ieee754].

<section class="installation">

## Installation

```bash
npm install @stdlib/constants-float64-min-base10-exponent
```

</section>

<section class="usage">

## Usage

<!-- eslint-disable id-length -->

```javascript
var FLOAT64_MIN_BASE10_EXPONENT = require( '@stdlib/constants-float64-min-base10-exponent' );
```

#### FLOAT64_MIN_BASE10_EXPONENT

The minimum base 10 exponent for a normal [double-precision floating-point number][ieee754].

<!-- eslint-disable id-length -->

```javascript
var bool = ( FLOAT64_MIN_BASE10_EXPONENT === -308 );
// returns true
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better example -->

<!-- eslint no-undef: "error" -->

<!-- eslint-disable id-length -->

```javascript
var FLOAT64_MIN_BASE10_EXPONENT = require( '@stdlib/constants-float64-min-base10-exponent' );

console.log( FLOAT64_MIN_BASE10_EXPONENT );
// => -308
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   [`@stdlib/constants/float64/max-base10-exponent`][@stdlib/constants/float64/max-base10-exponent]: the maximum base 10 exponent for a double-precision floating-point number.
-   [`@stdlib/constants/float64/min-base10-exponent-subnormal`][@stdlib/constants/float64/min-base10-exponent-subnormal]: the minimum base 10 exponent for a subnormal double-precision floating-point number.
-   [`@stdlib/constants/float64/min-base2-exponent`][@stdlib/constants/float64/min-base2-exponent]: the minimum biased base 2 exponent for a normal double-precision floating-point number.

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

## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/constants-float64-min-base10-exponent.svg
[npm-url]: https://npmjs.org/package/@stdlib/constants-float64-min-base10-exponent

[test-image]: https://github.com/stdlib-js/constants-float64-min-base10-exponent/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/constants-float64-min-base10-exponent/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/constants-float64-min-base10-exponent/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/constants-float64-min-base10-exponent?branch=main

[dependencies-image]: https://img.shields.io/david/stdlib-js/constants-float64-min-base10-exponent.svg
[dependencies-url]: https://david-dm.org/stdlib-js/constants-float64-min-base10-exponent/main

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[ieee754]: https://en.wikipedia.org/wiki/IEEE_754-1985

<!-- <related-links> -->

[@stdlib/constants/float64/max-base10-exponent]: https://github.com/stdlib-js/constants-float64-max-base10-exponent

[@stdlib/constants/float64/min-base10-exponent-subnormal]: https://github.com/stdlib-js/constants-float64-min-base10-exponent-subnormal

[@stdlib/constants/float64/min-base2-exponent]: https://github.com/stdlib-js/constants-float64-min-base2-exponent

<!-- </related-links> -->

</section>

<!-- /.links -->
