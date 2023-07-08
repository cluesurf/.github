<br/>
<br/>
<br/>

<p align='center'><img src='https://github.com/tunebond/.github/blob/make/view/mountains.svg?raw=true' height='256'></a></p>

<p align='center'><img src='https://github.com/tunebond/.github/blob/make/view/monkey.svg?raw=true' height='256'></a></p>

<p align='center'><em>
Way back in a simpler time<br/>
The great mother showed you rhyme<br/>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'><em>
Within networks cool and keen<br/>
The <a href='https://github.com/tunebond/tone'>tone</a> vibes pleasantly between<br/>
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
The <a href='https://github.com/tunebond/base.link'>base</a> <a href='https://github.com/tunebond/link'>link</a> knows to plant the seed<br/>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'>
  <img src='https://github.com/tunebond/.github/blob/make/view/bush.svg?raw=true' height='312'>
</p>

## Introduction

Welcome to TuneBond's page. We work with a few main things:

1. **software**: Open source software experimentation is our passion project.
1. **knowledge**: Understanding how the universe works and modeling information is our main drive.
1. **language**: Modeling things in natural language or code gives a deeper sense of reality.
1. **story**: Sharing what we've learned in the form of stories or philosophical conversations.

TuneBond is basically trying to synthesize and simplify the knowledge of the world so it boils down to something you could hold in your hand. Something where you can have a wide and at the same time deep sense of how the universe works. As such, we've created a few sites to share what we've come up with so far, even though it is far far from being "finished". Each of these projects are very much a work in progress, most of them are just in the creative design phase, with some basic development underway.

|                                                              Site                                                              | Note                                                                                                              |
| :----------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------- |
|                                                [`base.link`](https://base.link)                                                | **The Base Link Programming Language**                                                                            |
| <a href="https://base.link"><img src='https://github.com/tunebond/base.link/blob/make/view/base.svg?raw=true' height="92"></a> | A "modeling language" where you write in concise and minimalistic trees of text.                                  |
|                                                [`tone.rest`](https://tone.rest)                                                | **The Tone Writing System**                                                                                       |
|  <a href="https://tone.rest"><img src='https://github.com/tunebond/.github/blob/make/view/owl.svg?raw=true' height="92"></a>   | A simplified and uniform writing system for all the languages of Earth.                                           |
|                                                [`bead.chat`](https://bead.chat)                                                | **The Bead Spoken Language**                                                                                      |
| <a href="https://bead.chat"><img src='https://github.com/tunebond/.github/blob/make/view/fungi.svg?raw=true' height="92"></a>  | A natural language of a minimal memorizable set of concepts, used to model and play with reality in a deeper way. |
|                                                [`beat.land`](https://beat.land)                                                | **The Beat Land Chronology**                                                                                      |
|  <a href="https://beat.land"><img src='https://github.com/tunebond/.github/blob/make/view/rock.svg?raw=true' height="92"></a>  | A modern mythology of the universe. The museum entrypoint itself.                                                 |
|                                                [`leaf.show`](https://leaf.show)                                                | **The Leaf Show**                                                                                                 |
|  <a href="https://leaf.show"><img src='https://github.com/tunebond/.github/blob/make/view/leaf.svg?raw=true' height="92"></a>  | A podcast, which includes interviews and thoughts about the universe.                                             |

## Open Source Software

One of our biggest passion projects is to have one programming language or tool to build all possibilities of software apps and libraries. Something like [Rails](https://rubyonrails.org), where everything is streamlined and out of the way so you can focus on your main task instead of wrangling code. Combined with something like [Haxe](https://haxe.org/) or [Dart](https://dart.dev/) where it compiles down to every platform natively. We are deep into the programming and computer science worlds, having been working toward this goal for several years. There's still a huge amount of work that remains to be done, and like mentioned earlier, we are still defining the look and feel of everything at this point, only barely scratching the surface in terms of making the code run.

We wrote [`link`](https://github.com/tunebond/link), a super minimal tree-based data modeling language sort of like YAML/JSON/XML, which is in some ways more readable and concise than them. That project is basically finished. The spec is defined in that repo, and a primitive parser is implemented to convert link text into a tree. The next step is taking the link tree and compiling it into runnable code via [`base.link`](https://github.com/tunebond/base.link).

The **goal** here is to create a suite of tools to write code in one language, Link, and have it work cross-platform in an optimized way. This means compiling the Link Text into Swift for iOS/MacOS/etc., Rust for Linux server-side, Kotlin for Android, and JavaScript for Windows, the Browser, and Node.js. But many of the projects are written in such a way as to be language agnostic. That is, you can use the definitions, which are written in `link`, as you would any JSON object in your standard programming language.

Once we can nail down a prototype implementation that works in at least JavaScript (Node.js and Browser), and either Swift or Rust, then we will start publicizing the results and asking for help. But currently things are fluctuating constantly so it might be too much to bring it out in the open (even though it's publicly open source). If you'd like to help though, even now, that would be totally wonderful, please reach out.

The following table outlines the key projects and their overall purpose, so you can see how the pieces of the puzzle fit together. This is mostly a love for learning, a journey to understand the fundamentals of building an optimized compiler.

<br/>
<br/>

|                                                                        Code                                                                        | Note                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                                     [`link`](https://github.com/tunebond/link)                                                     | **The Modeling Language**                                                                                                                                                                                                                                                                                                                                                                                  |
|      <a href="https://github.com/tunebond/link"><img src='https://github.com/tunebond/link/blob/make/view/link.svg?raw=true' width='128'></a>      | This is the "data modeling language" which [`base.link`](https://github.com/tunebond/base.link) extends into a programming language and environment. There's not much too this piece other than the syntax.                                                                                                                                                                                                |
|                                                [`base.link`](https://github.com/tunebond/base.link)                                                | **A Link Text Programming Framework**                                                                                                                                                                                                                                                                                                                                                                      |
| <a href="https://github.com/tunebond/base.link"><img src='https://github.com/tunebond/base.link/blob/make/view/base.svg?raw=true' width='128'></a> | This is one example tool for building [`link`](https://github.com/tunebond/link) programs. It is a Link Text package manager, as well as its compiler. The main [**docs**](https://github.com/tunebond/base.link/blob/make/book/tree/code-tree/base.link) are found there for all link-related projects.                                                                                                   |
|                                                [`bind.link`](https://github.com/tunebond/bind.link)                                                | **The Base Link Platform Binding Library**                                                                                                                                                                                                                                                                                                                                                                 |
| <a href="https://github.com/tunebond/bind.link"><img src='https://github.com/tunebond/bind.link/blob/make/view/view.svg?raw=true' height='92'></a> | This is a library of all the native _types_ for each programming language / environment (JavaScript, Swift, Rust, Kotlin). This gives us the information necessary to compile Link Text down to native code in each environment.                                                                                                                                                                           |
|                                                [`bolt.link`](https://github.com/tunebond/bolt.link)                                                | **The Base Link Standard Library**                                                                                                                                                                                                                                                                                                                                                                         |
| <a href="https://github.com/tunebond/bolt.link"><img src='https://github.com/tunebond/bolt.link/blob/make/view/view.svg?raw=true' height='92'></a> | This is the foundational standard library. It includes all your standard primitive data types, as well as other well-defined data models which are useful in standard apps. It implements these in Node.js, the Browser, Rust (Linux server-side), Swift, and Kotlin (down the road).                                                                                                                      |
|                                                [`mesh.link`](https://github.com/tunebond/mesh.link)                                                | **The Base Link Compiler Framework**                                                                                                                                                                                                                                                                                                                                                                       |
| <a href="https://github.com/tunebond/mesh.link"><img src='https://github.com/tunebond/mesh.link/blob/make/view/base.svg?raw=true' height='92'></a> | This is the compiler, which takes the Link Text AST and transforms it into an AST based on your structure definitions, and then does the typechecking and typeinference and such to verify its correctness statically. Then it generates the JS or other target language output.                                                                                                                           |
|                                                [`crow.link`](https://github.com/tunebond/crow.link)                                                | **The Base Link UI Framework**                                                                                                                                                                                                                                                                                                                                                                             |
| <a href="https://github.com/tunebond/crow.link"><img src='https://github.com/tunebond/crow.link/blob/make/view/view.svg?raw=true' height='92'></a> | This is eventually going to be the UI framework, encompassing what React.js does, and also handling other graphics related stuff.                                                                                                                                                                                                                                                                          |
|                                                [`nest.link`](https://github.com/tunebond/nest.link)                                                | **The Base Link Network Framework**                                                                                                                                                                                                                                                                                                                                                                        |
| <a href="https://github.com/tunebond/nest.link"><img src='https://github.com/tunebond/nest.link/blob/make/view/view.svg?raw=true' height='92'></a> | This is going to be the somewhat "web" framework, focusing on how to define URL matchers, initialize servers, and potentially do websockets and other network related stuff.                                                                                                                                                                                                                               |
|                                                [`star.link`](https://github.com/tunebond/star.link)                                                | **The Base Link Third-Party API Integration Library**                                                                                                                                                                                                                                                                                                                                                      |
| <a href="https://github.com/tunebond/star.link"><img src='https://github.com/tunebond/star.link/blob/make/view/view.svg?raw=true' width='128'></a> | This is a collection of REST (and potentially other) API endpoints, written in [`link`](https://github.com/tunebond/link). It is going to be used to provide integration with many services in the [`base.link`](https://github.com/tunebond/base.link) / [`link`](https://github.com/tunebond/link) ecosystem, though it is written in a language-agnostic way (i.e. you could use this in any language). |
|                                                [`tree.link`](https://github.com/tunebond/tree.link)                                                | **The Base Link Content Grammar Library**                                                                                                                                                                                                                                                                                                                                                                  |
| <a href="https://github.com/tunebond/tree.link"><img src='https://github.com/tunebond/tree.link/blob/make/view/base.svg?raw=true' width='128'></a> | This is a collection of "grammars", written in [`link`](https://github.com/tunebond/link). These are pattern recognizers for generating object structures out of text or binary strings, and doing the reverse, of generating text/binaries from objects. They are defined in a language agnostic way.                                                                                                     |
|                                                [`seed.link`](https://github.com/tunebond/seed.link)                                                | **The Base Link Math Library**                                                                                                                                                                                                                                                                                                                                                                             |
| <a href="https://github.com/tunebond/seed.link"><img src='https://github.com/tunebond/seed.link/blob/make/view/seed.svg?raw=true' width='128'></a> | This is a collection of mathematical formalizations, written in [`link`](https://github.com/tunebond/link). These are going to be used, following along the lines of the HoTT project, as a foundational model of mathematics for use in a programming environment.                                                                                                                                        |

<br/>
<br/>

We are just beginning, so _much_ work is being done on the specifications, with only rough prototype implementations to test out the specifications. Once we finish the specifications and base implementations, it should be a usable cross-platform environment. Please reach out to use by opening an issue in any of the projects or finding us on Twitter if you'd like to discuss, exchange ideas, or in other ways join in the fun.

## Information Curation

We have spent years curating content from the internet, with the goal of cleaning it up and making it freely available (like Wikipedia, for data people, researchers, software engineers, and the general public, etc.). We have gone through several iterations or generations of cleaned content and data, but never got to the point where we thought it was good enough to release.

## Data Modeling

This is the main goal of the whole project, to have a model of the universe, a working model, a way to understand how things work. In addition, there is the technical aspect of figuring out how to structure this data for computers. So we are constantly brainstorming ways to come up with models of things so they are easy for software engineers and computers to make use of.

## Podcasting

To start, we intensely want to figure out how the universe works and how to evolve toward a more peaceful world. We have a lot of questions about a web of topics, and truly want to understand how things work. The academic community, scientific community, open source community, historical community, and many other communities offer their knowledge in casual conversations on their specialties or areas of curiosity. We ask them questions about things we are wondering, and go with the flow in figuring things out to come up with a clearer picture of reality.

## Storytelling

On [`bead.chat`](https://bead.chat) we consider the origins and evolution of language in a hypothetical scenario. On [`beat.land`](https://beat.land) we coordinate scientific and spiritual knowledge into a mythology of our creation on Earth.

## Language Building

Like mentioned, [`bead`](https://bead.chat) is a language we derived from imagining an ancient stone-tool making monkey culture of the past, and evolved it into a modern language capable of representing all of modern concepts and knowledge, such as naming species and places and everything you can imagine. That is very much an evolving work-in-progress.

We also created [`tone`](https://tone.rest), a writing system for the languages of Earth. It is used in `bead` as the standard writing system as well.

## Music

We play with beats and rhythms and melodies to explore the evolution of our ancient ancestors through musical understanding.

<p align='center'><img src='https://github.com/tunebond/.github/blob/make/view/stream.svg?raw=true' height='512'></a></p>
