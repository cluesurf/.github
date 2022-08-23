
<br/>
<br/>
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

## Introduction

Team Drum Work (TDW) does a few main things:

- interviews
- open source software
- information curation
- data modeling

To support this effort, we sell some merch.

- t-shirts
- books

The t-shirts include nature images and nice words in various languages (so far). The books are printings of public domain material, mostly ancient texts.

## Interviews

To start, [@lancejpollard](https://twitter.com/lancejpollard) intensely wants to figure out how the universe works and how to evolve toward a more peaceful world. He has a lot of questions about a web of topics, and truly wants to understand how things work. The academic community, scientific community, open source community, historical community, and many other communities offer their knowledge in casual conversations on their specialties or areas of curiosity. We ask them questions about things we are wondering, and go with the flow in figuring things out to come up with a clearer picture of reality.

## Open Source Software

The **goal** here is to create a suite of tools to write code in one language ([`link`](https://github.com/drumworkteam/base)), and have it work cross-platform in an optimized way (Swift for iOS/MacOS/etc., Rust for Linux server-side, Kotlin for Android, and JavaScript for Windows and the Browser). But many of the projects are written in such a way as to be language agnostic. That is, you can use the definitions, which are written in `link`, as you would any JSON object in your standard programming language.

Once we can nail down a prototype implementation that works in at least JavaScript (Node.js and Browser), and either Swift or Rust, then we will start publicizing the results and asking for help. But currently things are fluctuating constantly so it might be too much to bring it out in the open (even though it's publicly open source). If you'd like to help though, even now, that would be totally wonderful, please reach out.

The following table outlines the key projects and their overall purpose, so you can see how the pieces of the puzzle fit together. This is mostly a love for learning, a journey to understand the fundamentals of building an optimized compiler.

## Information Curation

We have spent years curating content from the internet, with the goal of cleaning it up and making it freely available (like Wikipedia, for data people, researchers, software engineers, and the general public, etc.). We have gone through several iterations or generations of cleaned content and data, but never got to the point where we thought it was good enough to releasee.

So now we are working on the site [tree.surf](https://tree.surf) to publish all of the data and make it easy to use and learn from. Tree Surf is a community edited, curated "model of the world" website. It has tons of structured data of various kinds, and does as much as possible to structure the unstructured or difficult to structure data (like modeling people, or organizations). It is not like a news which has a constant stream of new information, instead we build on pieces of content like an organic encyclopedia, combined with an ever refining design, in as concise a way as possible so you can learn about everything. Like holding the seed of the universe.

All of the information we collect and the community can collect will be published to Tree Surf and refined, and stored so you can download a copy just in case. You can add data easily by cloning the [tree.surf GitHub repo](https://github.com/teamdrumwork/tree.surf) and adding in the `./contents` folder your structured data. See the readme in that project for more details.

## Data Modeling

This is the main goal of the whole project, to have a model of the universe, a working model, a way to understand how things work. In addition, there is the technical aspect of figuring out how to structure this data for computers. So we are constantly brainstorming ways to come up with models of things so they are easy for software engineers and computers to make use of.

<br/>
<br/>

| Code | Note |
|:----:|:----|
| [`base`](https://github.com/drumworkteam/base) | **The Link Text Compiler** |
| <a href="https://github.com/drumworkteam/base"><img src='https://github.com/drumworkteam/base/blob/make/view/base.svg?raw=true' height='128'></a> | This is the main tool for building [`link`](https://github.com/drumworkteam/link) programs. It is a Link Text package manager, as well as its compiler. The main [**docs**](https://github.com/drumworkteam/base/blob/make/book/tree/code-tree/base.link) are found there for all link-related projects. |
| [`link`](https://github.com/drumworkteam/link) | **The Data Modeling Language, Link** |
| <a href="https://github.com/drumworkteam/link"><img src='https://github.com/drumworkteam/link/blob/make/view/link.svg?raw=true' height='128'></a> | This is the "data modeling language" which [`base`](https://github.com/drumworkteam/base) extends into a programming language and environment. There's not much too this piece other than the syntax. |
| [`moon`](https://github.com/drumworkteam/moon) | **The Link Text Standard Library Specification** |
| <a href="https://github.com/drumworkteam/moon"><img src='https://github.com/drumworkteam/moon/blob/make/view/moon.svg?raw=true' height='128'></a> | This is the foundational standard library _specification_ (as opposed to implementation), for any programming language to use as the base. We are using this to define the standard library used by [`base`](https://github.com/drumworkteam/base) projects written in [`link`](https://github.com/drumworkteam/link). It aims to normalize the basic data types across programming language environments. |
| [`wolf`](https://github.com/drumworkteam/wolf) | **The Link Text Standard Library Implementation** |
| <a href="https://github.com/drumworkteam/wolf"><img src='https://github.com/drumworkteam/wolf/blob/make/view/view.svg?raw=true' height='128'></a> | This is the foundational standard library which implements the [`moon`](https://github.com/drumworkteam/moon) specification. It includes all your standard primitive data types, as well as other well-defined data models which are useful in standard apps. It implements `moon` in Node.js, the Browser, Rust (Linux server-side), Swift, and Kotlin (down the road). |
| [`tree`](https://github.com/drumworkteam/tree) | **The Link Text Framework Specification** |
| <a href="https://github.com/drumworkteam/tree"><img src='https://github.com/drumworkteam/tree/blob/make/view/view.svg?raw=true' height='128'></a> | This is an opinionated framework specification for [`base`](https://github.com/drumworkteam/base) projects written in [`link`](https://github.com/drumworkteam/link), like Ruby on Rails. Again, it is language-agnostic, just definining the API interface for programming languages to implement. |
| [`crow`](https://github.com/drumworkteam/crow) | **The Link Text Framework Implementation** |
| <a href="https://github.com/drumworkteam/crow"><img src='https://github.com/drumworkteam/crow/blob/make/view/view.svg?raw=true' height='128'></a> | This is a [`tree`](https://github.com/drumworkteam/tree) framework _implementation_, supporting Node.js, Browser, Swift (iOS, MacOS, etc.), Windows (JavaScript), Linux (Rust), and Kotlin (Android). It aims to provide a rich and robust cross-platform API to everything you need to build web apps. |
| [`seed`](https://github.com/drumworkteam/seed) | **The Link Text Platform Driver Library** |
| <a href="https://github.com/drumworkteam/seed"><img src='https://github.com/drumworkteam/seed/blob/make/view/view.svg?raw=true' height='128'></a> | This is a library of all the native _types_ for each programming language / environment (JavaScript, Swift, Rust, Kotlin). This gives us the information necessary to compile Link Text down to native code in each environment. |
| [`star`](https://github.com/drumworkteam/star) | **The Link Text Third-Party API Integration Library** |
| <a href="https://github.com/drumworkteam/star"><img src='https://github.com/drumworkteam/star/blob/make/view/view.svg?raw=true' height='128'></a> | This is a collection of REST (and potentially other) API endpoints, written in [`link`](https://github.com/drumworkteam/link). It is going to be used to provide integration with many services in the [`base`](https://github.com/drumworkteam/base) / [`link`](https://github.com/drumworkteam/link) ecosystem, though it is written in a language-agnostic way (i.e. you could use this in any language). |
| [`fish`](https://github.com/drumworkteam/fish) | **The Link Text Content Grammar Library** |
| <a href="https://github.com/drumworkteam/fish"><img src='https://github.com/drumworkteam/fish/blob/make/view/view.svg?raw=true' height='128'></a> | This is a collection of "grammars", written in [`link`](https://github.com/drumworkteam/link). These are pattern recognizers for generating object structures out of text or binary strings, and doing the reverse, of generating text/binaries from objects. They are defined in a language agnostic way. |
| [`rock`](https://github.com/drumworkteam/rock) | **The Link Text Math Structure and Definition Library** |
| <a href="https://github.com/drumworkteam/rock"><img src='https://github.com/drumworkteam/rock/blob/make/view/view.svg?raw=true' height='128'></a> | This is a collection of mathematical formalizations, written in [`link`](https://github.com/drumworkteam/link). These are going to be used, following along the lines of the HoTT project, as a foundational model of mathematics for use in a programming environment. |

<br/>
<br/>

We are just beginning, so much work is being done on the specifications, with only rough prototype implementations to test out the specifications. Once we finish the specifications and base implementations, it should be a usable cross-platform environment. Please reach out to use by opening an issue in any of the projects or finding us on Twitter if you'd like to discuss, exchange ideas, or in other ways join in the fun.

