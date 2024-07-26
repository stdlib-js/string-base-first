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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# first

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Return the first `n` UTF-16 code units of a string.



<section class="usage">

## Usage

```javascript
import first from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@esm/index.mjs';
```
The previous example will load the latest bundled code from the esm branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/string-base-first/tags). For example,

```javascript
import first from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@v0.2.2-esm/index.mjs';
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
<script type="module">

import first from 'https://cdn.jsdelivr.net/gh/stdlib-js/string-base-first@esm/index.mjs';

var str = first( 'presidential election', 1 );
// returns 'p'

str = first( 'JavaScript', 1 );
// returns 'J'

str = first( 'The Last of the Mohicans', 5 );
// returns 'The L'

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/string-base/first-code-point`][@stdlib/string/base/first-code-point]</span><span class="delimiter">: </span><span class="description">return the first Unicode code point of a string.</span>
-   <span class="package-name">[`@stdlib/string-base/first-grapheme-cluster`][@stdlib/string/base/first-grapheme-cluster]</span><span class="delimiter">: </span><span class="description">return the first grapheme cluster (i.e., user-perceived character) of a string.</span>
-   <span class="package-name">[`@stdlib/string-base/last`][@stdlib/string/base/last]</span><span class="delimiter">: </span><span class="description">return the last UTF-16 code unit of a string.</span>
-   <span class="package-name">[`@stdlib/string-base/remove-first`][@stdlib/string/base/remove-first]</span><span class="delimiter">: </span><span class="description">remove the first UTF-16 code unit of a string.</span>
-   <span class="package-name">[`@stdlib/string-first`][@stdlib/string/first]</span><span class="delimiter">: </span><span class="description">return the first character(s) of a string.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/string-base-first.svg
[npm-url]: https://npmjs.org/package/@stdlib/string-base-first

[test-image]: https://github.com/stdlib-js/string-base-first/actions/workflows/test.yml/badge.svg?branch=v0.2.2
[test-url]: https://github.com/stdlib-js/string-base-first/actions/workflows/test.yml?query=branch:v0.2.2

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
[deno-readme]: https://github.com/stdlib-js/string-base-first/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/string-base-first/tree/umd
[umd-readme]: https://github.com/stdlib-js/string-base-first/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/string-base-first/tree/esm
[esm-readme]: https://github.com/stdlib-js/string-base-first/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/string-base-first/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/string-base-first/main/LICENSE

<!-- <related-links> -->

[@stdlib/string/base/first-code-point]: https://github.com/stdlib-js/string-base-first-code-point/tree/esm

[@stdlib/string/base/first-grapheme-cluster]: https://github.com/stdlib-js/string-base-first-grapheme-cluster/tree/esm

[@stdlib/string/base/last]: https://github.com/stdlib-js/string-base-last/tree/esm

[@stdlib/string/base/remove-first]: https://github.com/stdlib-js/string-base-remove-first/tree/esm

[@stdlib/string/first]: https://github.com/stdlib-js/string-first/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
