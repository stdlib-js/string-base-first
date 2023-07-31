<!--

@license Apache-2.0

Copyright (c) 2023 The Stdlib Authors.

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

# first

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Return the first `n` UTF-16 code units of a string.



<section class="usage">

## Usage

To use in Observable,

```javascript
first = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@umd/browser.js' )
```
The previous example will load the latest bundled code from the umd branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/string-base-first/tags). For example,

```javascript
first = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@v0.0.1-umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var first = require( 'path/to/vendor/umd/string-base-first/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.first;
})();
</script>
```

#### first( str, n )

Returns the first `n` UTF-16 code units of a string.

```javascript
var out = first( 'last man standing', 1 );
// returns 'l'

out = first( 'Hidden Treasures', 1 );
// returns 'H'

out = first( 'foo bar', 5 );
// returns 'foo b'

out = first( 'foo bar', 10 );
// returns 'foo bar'
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@umd/browser.js"></script>
<script type="text/javascript">
(function () {

var str = first( 'presidential election', 1 );
// returns 'p'

str = first( 'JavaScript', 1 );
// returns 'J'

str = first( 'The Last of the Mohicans', 5 );
// returns 'The L'

})();
</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

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

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-base-first.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-base-first

[test-image]: https://github.com/stdlib-js/string-base-first/actions/workflows/test.yml/badge.svg?branch=v0.0.1
[test-url]: https://github.com/stdlib-js/string-base-first/actions/workflows/test.yml?query=branch:v0.0.1

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/string-base-first/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/string-base-first?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/string-base-first.svg
[dependencies-url]: https://david-dm.org/stdlib-js/string-base-first/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/string-base-first/tree/deno
[umd-url]: https://github.com/stdlib-js/string-base-first/tree/umd
[esm-url]: https://github.com/stdlib-js/string-base-first/tree/esm
[branches-url]: https://github.com/stdlib-js/string-base-first/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-base-first/main/LICENSE

</section>

<!-- /.links -->
