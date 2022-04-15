
<br/>
<br/>
<br/>

<p align='center'>
  <img src='https://github.com/drumworkteam/.github/blob/make/view/drum.svg?raw=true' height='256'>
</p>

<br/>

<p align='center'><em>
Way back in a simpler time<br/>
The great mother showed you rhyme<br/>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'><em>
Within networks cool and keen<br/>
The <a href='https://github.com/drumworkteam/tone'>tone</a> <a href='https://github.com/drumworkteam/tune'>tune</a> vibes pleasantly between<br/>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'><em>
Way down in the feeling tree<br/>
The mind calms and urges lead<br/>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'><em>
Use your heart to find the key<br/>
The <a href='https://github.com/drumworkteam/base'>base</a> <a href='https://github.com/drumworkteam/link'>link</a> knows to plant the seed<br/>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'>
  <img src='https://github.com/drumworkteam/.github/blob/make/view/bush.svg?raw=true' height='312'>
</p>

| codebase | description |
|:----:|:----|
| [`base`](https://github.com/drumworkteam/base) | **The Link Text Compiler** |
| <a href="https://github.com/drumworkteam/base"><img src='https://github.com/drumworkteam/base/blob/make/view/view.svg?raw=true' height='128'></a> | This is the main tool for building [`link`](https://github.com/drumworkteam/link) programs. It is a Link Text package manager, as well as its compiler. The main **docs** are found there for all link-related projects. |
| [`link`](https://github.com/drumworkteam/link) | **The Data Modeling Language, Link** |
| <a href="https://github.com/drumworkteam/link"><img src='https://github.com/drumworkteam/link/blob/make/view/link.svg?raw=true' height='128'></a> | This is the "data modeling language" which [`base`](https://github.com/drumworkteam/base) extends into a programming language and environment. There's not much too this piece other than the syntax. |
| [`moon`](https://github.com/drumworkteam/moon) | **The Link Text Standard Library Specification** |
| <a href="https://github.com/drumworkteam/moon"><img src='https://github.com/drumworkteam/moon/blob/make/view/moon.svg?raw=true' height='128'></a> | This is the foundational standard library _specification_ (as opposed to implementation), for any programming language to use as the base. We are using this to define the standard library used by [`base`](https://github.com/drumworkteam/base) projects written in [`link`](https://github.com/drumworkteam/link). |
| [`wolf`](https://github.com/drumworkteam/wolf) | **The Link Text Standard Library Implementation** |
| <a href="https://github.com/drumworkteam/wolf"><img src='https://github.com/drumworkteam/wolf/blob/make/view/view.svg?raw=true' height='128'></a> | This is the foundational standard library which implements the [`moon`](https://github.com/drumworkteam/moon) specification. It includes all your standard primitive data types, as well as other well-defined data models which are useful in standard apps. It implements `moon` in Node.js, the Browser, Rust (Linux server-side), Swift, and Kotlin (down the road). |
| [`tree`](https://github.com/drumworkteam/tree) | **The Link Text Framework Specification** |
| <a href="https://github.com/drumworkteam/tree"><img src='https://github.com/drumworkteam/tree/blob/make/view/tree.svg?raw=true' height='128'></a> | This is an opinionated framework specification for [`base`](https://github.com/drumworkteam/base) projects written in [`link`](https://github.com/drumworkteam/link), like Ruby on Rails. Again, it is language-agnostic, just definining the API interface for programming languages to implement. |
| [`crow`](https://github.com/drumworkteam/crow) | **The Link Text Framework Implementation** |
| <a href="https://github.com/drumworkteam/crow"><img src='https://github.com/drumworkteam/crow/blob/make/view/tree.svg?raw=true' height='128'></a> | This is a [`tree`](https://github.com/drumworkteam/tree) framework _implementation_, supporting Node.js, Browser, Swift (iOS, MacOS, etc.), Windows (JavaScript), Linux (Rust) and Kotlin (Android). It aims to provide a rich and robust cross-platform API to everything you need to build web apps. |
| [`seed`](https://github.com/drumworkteam/seed) | **The Link Text Platform Drivers** |
| <a href="https://github.com/drumworkteam/seed"><img src='https://github.com/drumworkteam/seed/blob/make/view/tree.svg?raw=true' height='128'></a> | This is a library of all the native _types_ for each programming language / environment (JavaScript, Swift, Rust, Kotlin). This gives us the information necessary to compile Link Text down to native code in each environment. |
| [`star`](https://github.com/drumworkteam/star) | **The Link Text Third-Party API Integration Library** |
| <a href="https://github.com/drumworkteam/star"><img src='https://github.com/drumworkteam/star/blob/make/view/tree.svg?raw=true' height='128'></a> | This is a collection of REST (and potentially other) API endpoints, written in [`link`](https://github.com/drumworkteam/link). It is going to be used to provide integration with many services in the [`base`](https://github.com/drumworkteam/base) / [`link`](https://github.com/drumworkteam/link) ecosystem. |
| [`fish`](https://github.com/drumworkteam/fish) | **The Link Text Content Grammar Library** |
| <a href="https://github.com/drumworkteam/fish"><img src='https://github.com/drumworkteam/fish/blob/make/view/tree.svg?raw=true' height='128'></a> | This is a collection of "grammars", written in [`link`](https://github.com/drumworkteam/link). These are pattern recognizers for generating object structures out of text or binary strings, and doing the reverse, of generating text/binaries from objects. They are defined in a language agnostic way. |
| [`rock`](https://github.com/drumworkteam/rock) | **The Link Text Math Structures and Definition Library** |
| <a href="https://github.com/drumworkteam/rock"><img src='https://github.com/drumworkteam/rock/blob/make/view/tree.svg?raw=true' height='128'></a> | This is a collection of mathematical formalizations, written in [`link`](https://github.com/drumworkteam/link). These are going to be used, following along the lines of the HoTT project, as a foundational model of mathematics for use in a programming environment. |

We are just beginning, so much work is being done on the specifications, with only rough prototype implementations to test out the specifications. Once we finish the specifications and base implementations, it should be a usable cross-platform environment. Please reach out to use by opening an issue in any of the projects or finding us on Twitter if you'd like to discuss, exchange ideas, or in other ways join in the fun.
