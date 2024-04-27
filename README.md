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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Regular Expressions

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Regular expressions.

<section class="installation">

## Installation

```bash
npm install @bobyzgirlllnpm/iure-ipsum-sint
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var regexp = require( '@bobyzgirlllnpm/iure-ipsum-sint' );
```

#### regexp

Namespace containing regular expressions.

```javascript
var re = regexp;
// returns {...}
```

The following regular expressions are currently exported:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`reBasenamePosix()`][@bobyzgirlllnpm/iure-ipsum-sint/basename-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a POSIX path.</span>
-   <span class="signature">[`reBasenameWindows()`][@bobyzgirlllnpm/iure-ipsum-sint/basename-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a Windows path.</span>
-   <span class="signature">[`reBasename( [platform] )`][@bobyzgirlllnpm/iure-ipsum-sint/basename]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a path.</span>
-   <span class="signature">[`reColorHexadecimal( [mode] )`][@bobyzgirlllnpm/iure-ipsum-sint/color-hexadecimal]</span><span class="delimiter">: </span><span class="description">regular expression to match a hexadecimal color.</span>
-   <span class="signature">[`reDecimalNumber( [options] )`][@bobyzgirlllnpm/iure-ipsum-sint/decimal-number]</span><span class="delimiter">: </span><span class="description">regular expression to match a decimal number.</span>
-   <span class="signature">[`reDirnamePosix()`][@bobyzgirlllnpm/iure-ipsum-sint/dirname-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture a POSIX path dirname.</span>
-   <span class="signature">[`reDirnameWindows()`][@bobyzgirlllnpm/iure-ipsum-sint/dirname-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture a Windows path dirname.</span>
-   <span class="signature">[`reDirname( [platform] )`][@bobyzgirlllnpm/iure-ipsum-sint/dirname]</span><span class="delimiter">: </span><span class="description">regular expression to capture a path dirname.</span>
-   <span class="signature">[`reDurationString()`][@bobyzgirlllnpm/iure-ipsum-sint/duration-string]</span><span class="delimiter">: </span><span class="description">regular expression to match a duration string.</span>
-   <span class="signature">[`reEOL( [options] )`][@bobyzgirlllnpm/iure-ipsum-sint/eol]</span><span class="delimiter">: </span><span class="description">regular expression to match a newline character sequence.</span>
-   <span class="signature">[`reExtendedLengthPath()`][@bobyzgirlllnpm/iure-ipsum-sint/extended-length-path]</span><span class="delimiter">: </span><span class="description">regular expression to detect an extended-length path.</span>
-   <span class="signature">[`reExtnamePosix()`][@bobyzgirlllnpm/iure-ipsum-sint/extname-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture a POSIX filename extension.</span>
-   <span class="signature">[`reExtnameWindows()`][@bobyzgirlllnpm/iure-ipsum-sint/extname-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture a Windows filename extension.</span>
-   <span class="signature">[`reExtname( [platform] )`][@bobyzgirlllnpm/iure-ipsum-sint/extname]</span><span class="delimiter">: </span><span class="description">regular expression to capture a filename extension.</span>
-   <span class="signature">[`reFilenamePosix()`][@bobyzgirlllnpm/iure-ipsum-sint/filename-posix]</span><span class="delimiter">: </span><span class="description">regular expression to split a POSIX filename.</span>
-   <span class="signature">[`reFilenameWindows()`][@bobyzgirlllnpm/iure-ipsum-sint/filename-windows]</span><span class="delimiter">: </span><span class="description">regular expression to split a Windows filename.</span>
-   <span class="signature">[`reFilename( [platform] )`][@bobyzgirlllnpm/iure-ipsum-sint/filename]</span><span class="delimiter">: </span><span class="description">regular expression to split a filename.</span>
-   <span class="signature">[`reFunctionName()`][@bobyzgirlllnpm/iure-ipsum-sint/function-name]</span><span class="delimiter">: </span><span class="description">regular expression to capture a function name.</span>
-   <span class="signature">[`reNativeFunction()`][@bobyzgirlllnpm/iure-ipsum-sint/native-function]</span><span class="delimiter">: </span><span class="description">regular expression to match a native function.</span>
-   <span class="signature">[`reRegExp()`][@bobyzgirlllnpm/iure-ipsum-sint/regexp]</span><span class="delimiter">: </span><span class="description">regular expression to parse a regular expression string.</span>
-   <span class="signature">[`reviveRegExp( key, value )`][@bobyzgirlllnpm/iure-ipsum-sint/reviver]</span><span class="delimiter">: </span><span class="description">revive a JSON-serialized regular expression.</span>
-   <span class="signature">[`reSemVer()`][@bobyzgirlllnpm/iure-ipsum-sint/semver]</span><span class="delimiter">: </span><span class="description">regular expression to match a semantic version string.</span>
-   <span class="signature">[`regexp2json( regexp )`][@bobyzgirlllnpm/iure-ipsum-sint/to-json]</span><span class="delimiter">: </span><span class="description">return a JSON representation of a regular expression.</span>
-   <span class="signature">[`reUncPath()`][@bobyzgirlllnpm/iure-ipsum-sint/unc-path]</span><span class="delimiter">: </span><span class="description">regular expression to parse a UNC path.</span>
-   <span class="signature">[`reUtf16SurrogatePair()`][@bobyzgirlllnpm/iure-ipsum-sint/utf16-surrogate-pair]</span><span class="delimiter">: </span><span class="description">regular expression to match a UTF-16 surrogate pair.</span>
-   <span class="signature">[`reUtf16UnpairedSurrogate()`][@bobyzgirlllnpm/iure-ipsum-sint/utf16-unpaired-surrogate]</span><span class="delimiter">: </span><span class="description">regular expression to match an unpaired UTF-16 surrogate.</span>
-   <span class="signature">[`reWhitespace( [options] )`][@bobyzgirlllnpm/iure-ipsum-sint/whitespace]</span><span class="delimiter">: </span><span class="description">regular expression to match a white space character.</span>

</div>

<!-- </toc> -->

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var regexp = require( '@bobyzgirlllnpm/iure-ipsum-sint' );

console.log( objectKeys( regexp ) );
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

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@bobyzgirlllnpm/iure-ipsum-sint.svg
[npm-url]: https://npmjs.org/package/@bobyzgirlllnpm/iure-ipsum-sint

[test-image]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/bobyzgirlllnpm/iure-ipsum-sint/main.svg
[coverage-url]: https://codecov.io/github/bobyzgirlllnpm/iure-ipsum-sint?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/bobyzgirlllnpm/iure-ipsum-sint.svg
[dependencies-url]: https://david-dm.org/bobyzgirlllnpm/iure-ipsum-sint/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/deno
[deno-readme]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/blob/deno/README.md
[umd-url]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/umd
[umd-readme]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/blob/umd/README.md
[esm-url]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/esm
[esm-readme]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/blob/esm/README.md
[branches-url]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/bobyzgirlllnpm/iure-ipsum-sint/main/LICENSE

<!-- <toc-links> -->

[@bobyzgirlllnpm/iure-ipsum-sint/basename-posix]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/basename-posix

[@bobyzgirlllnpm/iure-ipsum-sint/basename-windows]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/basename-windows

[@bobyzgirlllnpm/iure-ipsum-sint/basename]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/basename

[@bobyzgirlllnpm/iure-ipsum-sint/color-hexadecimal]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/color-hexadecimal

[@bobyzgirlllnpm/iure-ipsum-sint/decimal-number]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/decimal-number

[@bobyzgirlllnpm/iure-ipsum-sint/dirname-posix]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/dirname-posix

[@bobyzgirlllnpm/iure-ipsum-sint/dirname-windows]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/dirname-windows

[@bobyzgirlllnpm/iure-ipsum-sint/dirname]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/dirname

[@bobyzgirlllnpm/iure-ipsum-sint/duration-string]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/duration-string

[@bobyzgirlllnpm/iure-ipsum-sint/eol]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/eol

[@bobyzgirlllnpm/iure-ipsum-sint/extended-length-path]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/extended-length-path

[@bobyzgirlllnpm/iure-ipsum-sint/extname-posix]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/extname-posix

[@bobyzgirlllnpm/iure-ipsum-sint/extname-windows]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/extname-windows

[@bobyzgirlllnpm/iure-ipsum-sint/extname]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/extname

[@bobyzgirlllnpm/iure-ipsum-sint/filename-posix]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/filename-posix

[@bobyzgirlllnpm/iure-ipsum-sint/filename-windows]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/filename-windows

[@bobyzgirlllnpm/iure-ipsum-sint/filename]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/filename

[@bobyzgirlllnpm/iure-ipsum-sint/function-name]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/function-name

[@bobyzgirlllnpm/iure-ipsum-sint/native-function]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/native-function

[@bobyzgirlllnpm/iure-ipsum-sint/regexp]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/regexp

[@bobyzgirlllnpm/iure-ipsum-sint/reviver]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/reviver

[@bobyzgirlllnpm/iure-ipsum-sint/semver]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/semver

[@bobyzgirlllnpm/iure-ipsum-sint/to-json]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/to-json

[@bobyzgirlllnpm/iure-ipsum-sint/unc-path]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/unc-path

[@bobyzgirlllnpm/iure-ipsum-sint/utf16-surrogate-pair]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/utf16-surrogate-pair

[@bobyzgirlllnpm/iure-ipsum-sint/utf16-unpaired-surrogate]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/utf16-unpaired-surrogate

[@bobyzgirlllnpm/iure-ipsum-sint/whitespace]: https://github.com/bobyzgirlllnpm/iure-ipsum-sint/tree/main/whitespace

<!-- </toc-links> -->

</section>

<!-- /.links -->
