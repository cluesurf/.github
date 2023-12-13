<br/>
<br/>
<br/>

<p align='center'><img src='https://github.com/termsurf/.github/blob/make/view/mountains.svg?raw=true' height='256'></a></p>

<p align='center'><img src='https://github.com/termsurf/.github/blob/make/view/monkey.svg?raw=true' height='256'></a></p>

<p align='center'><em>
Way back in a simpler time<br/>
The great mother showed you rhyme<br/>
</em></p>

<p align='center'><em>
Way down in the feeling tree<br/>
The mind calms and urges lead<br/>
</em></p>

<p align='center'><em>
Use your heart to find the key<br/>
The <a href='https://github.com/termsurf/base.note'>base</a> <a href='https://github.com/termsurf/link'>link</a> plants the seed<br/>
</em></p>

<p align='center'><em>
A dark energy finds your need<br/>
And appeals to you through hide and seek<br/>
</em></p>

<p align='center'>
  <img src='https://github.com/termsurf/.github/blob/make/view/bush.svg?raw=true' height='312'>
</p>

## Introduction

Welcome to TermSurf's page, focusing on a few main things:

1. **software**: Open source software experimentation is the passion project.
1. **knowledge**: Understanding how the universe works and modeling information is the main drive.
1. **language**: Modeling things in natural language or code gives a deeper sense of reality.
1. **story**: Sharing learnings in the form of stories or philosophical conversations.

TermSurf is basically trying to synthesize and simplify the knowledge of the world so it boils down to something you could hold in your hand. Something where you can have a wide and at the same time deep sense of how the universe works. As such, here a few sites to share what's been come up with so far, even though it is far far from being "finished". Each of these projects are very much a work in progress, most of them are just in the creative design phase, with some basic development underway.

|                                                              Site                                                              | Note                                                                                                              |
| :----------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------- |
|                                                [`tune.surf`](https://tune.surf)                                                | **The Tune Spoken Language**                                                                                      |
|   <a href="https://tune.surf"><img src='https://github.com/termsurf/tune/blob/make/view/bird.svg?raw=true' height="92"></a>    | A natural language of a minimal memorizable set of concepts, used to model and play with reality in a deeper way. |
|                                                [`tone.surf`](https://tone.surf)                                                | **The Tone Writing System**                                                                                       |
|  <a href="https://tone.surf"><img src='https://github.com/termsurf/.github/blob/make/view/owl.svg?raw=true' height="92"></a>   | A simplified and uniform writing system for all the languages of Earth.                                           |
|                                                [`form.surf`](https://form.surf)                                                | **World Form Definition Wiki**                                                                                    |
|  <a href="https://form.surf"><img src='https://github.com/termsurf/.github/blob/make/view/rock.svg?raw=true' height="92"></a>  | A modern model of the universe. The museum entrypoint itself.                                                     |
|                                                [`base.surf`](https://base.surf)                                                | **The BaseNote Package Manager**                                                                                  |
| <a href="https://base.surf"><img src='https://github.com/termsurf/base.note/blob/make/view/base.svg?raw=true' height="92"></a> | A "modeling language" where you write in concise and minimalistic trees of text.                                  |

## Open Source Software

The main passion project is to have one programming language or tool to build all possibilities of software apps and libraries. Something like [Rails](https://rubyonrails.org), where everything is streamlined and out of the way so you can focus on your main task instead of wrangling code. Combined with something like [Haxe](https://haxe.org/) or [Dart](https://dart.dev/) where it compiles down to every platform natively. We are deep into the programming and computer science worlds, having been working toward this goal for several years. There's still a huge amount of work that remains to be done, and like mentioned earlier, the look and feel of everything is still being defined at this point, only barely scratching the surface in terms of making the code run.

There is [`note`](https://github.com/termsurf/note), a super minimal tree-based data modeling language sort of like YAML/JSON/XML, which is in some ways more readable and concise than them. That project is basically finished. The spec is defined in that repo, and a primitive parser is implemented to convert link text into a tree. The next step is taking the link tree and compiling it into runnable code via [`base.note`](https://github.com/termsurf/base.note).

The **goal** here is to create a suite of tools to write code in one language, Link, and have it work cross-platform in an optimized way. This means compiling the Link Text into Swift for iOS/MacOS/etc., Rust for Linux server-side, Kotlin for Android, and JavaScript for Windows, the Browser, and Node.js. But many of the projects are written in such a way as to be language agnostic. That is, you can use the definitions, which are written in `note`, as you would any JSON object in your standard programming language.

Once we can nail down a prototype implementation that works in at least JavaScript (Node.js and Browser), and either Swift or Rust, then we will start publicizing the results and asking for help. But currently things are fluctuating constantly so it might be too much to bring it out in the open (even though it's publicly open source). If you'd like to help though, even now, that would be totally wonderful, please reach out.

The following table outlines the key projects and their overall purpose, so you can see how the pieces of the puzzle fit together. This is mostly a love for learning, a journey to understand the fundamentals of building an optimized compiler.

<br/>
<br/>

|                                                                        Code                                                                        | Note                                                                                                                                                                                                                                                                                                                                                                                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                                     [`note`](https://github.com/termsurf/note)                                                     | **The Modeling Language**                                                                                                                                                                                                                                                                                                                                                                                  |
|      <a href="https://github.com/termsurf/note"><img src='https://github.com/termsurf/note/blob/make/view/link.svg?raw=true' width='128'></a>      | This is the "data modeling language" which [`base.note`](https://github.com/termsurf/base.note) extends into a programming language and environment. There's not much too this piece other than the syntax.                                                                                                                                                                                                |
|                                                [`base.note`](https://github.com/termsurf/base.note)                                                | **A Link Text Programming Framework**                                                                                                                                                                                                                                                                                                                                                                      |
| <a href="https://github.com/termsurf/base.note"><img src='https://github.com/termsurf/base.note/blob/make/view/base.svg?raw=true' width='128'></a> | This is one example tool for building [`note`](https://github.com/termsurf/link) programs. It is a Link Text package manager, as well as its compiler. The main [docs]https://github.com/termsurf/base.note/blob/make/book) are found there for all link-related projects.                                                                                                                                 |
|                                                [`bind.note`](https://github.com/termsurf/bind.note)                                                | **The BaseNote Platform Binding Library**                                                                                                                                                                                                                                                                                                                                                                  |
| <a href="https://github.com/termsurf/bind.note"><img src='https://github.com/termsurf/bind.note/blob/make/view/view.svg?raw=true' height='92'></a> | This is a library of all the native _types_ for each programming language / environment (JavaScript, Swift, Rust, Kotlin). This gives us the information necessary to compile Link Text down to native code in each environment.                                                                                                                                                                           |
|                                                [`bolt.note`](https://github.com/termsurf/bolt.note)                                                | **The BaseNote Standard Library**                                                                                                                                                                                                                                                                                                                                                                          |
| <a href="https://github.com/termsurf/bolt.note"><img src='https://github.com/termsurf/bolt.note/blob/make/view/view.svg?raw=true' height='92'></a> | This is the foundational standard library. It includes all your standard primitive data types, as well as other well-defined data models which are useful in standard apps. It implements these in Node.js, the Browser, Rust (Linux server-side), Swift, and Kotlin (down the road).                                                                                                                      |
|                                                [`mesh.note`](https://github.com/termsurf/mesh.note)                                                | **The BaseNote Compiler Framework**                                                                                                                                                                                                                                                                                                                                                                        |
| <a href="https://github.com/termsurf/mesh.note"><img src='https://github.com/termsurf/mesh.note/blob/make/view/base.svg?raw=true' height='92'></a> | This is the compiler, which takes the Link Text AST and transforms it into an AST based on your structure definitions, and then does the typechecking and typeinference and such to verify its correctness statically. Then it generates the JS or other target language output.                                                                                                                           |
|                                                [`crow.note`](https://github.com/termsurf/crow.note)                                                | **The BaseNote UI Framework**                                                                                                                                                                                                                                                                                                                                                                              |
| <a href="https://github.com/termsurf/crow.note"><img src='https://github.com/termsurf/crow.note/blob/make/view/view.svg?raw=true' height='92'></a> | This is eventually going to be the UI framework, encompassing what React.js does, and also handling other graphics related stuff.                                                                                                                                                                                                                                                                          |
|                                                [`star.note`](https://github.com/termsurf/star.note)                                                | **The BaseNote Third-Party API Integration Library**                                                                                                                                                                                                                                                                                                                                                       |
| <a href="https://github.com/termsurf/star.note"><img src='https://github.com/termsurf/star.note/blob/make/view/view.svg?raw=true' width='128'></a> | This is a collection of REST (and potentially other) API endpoints, written in [`note`](https://github.com/termsurf/link). It is going to be used to provide integration with many services in the [`base.note`](https://github.com/termsurf/base.note) / [`note`](https://github.com/termsurf/link) ecosystem, though it is written in a language-agnostic way (i.e. you could use this in any language). |
|                                                [`worm.note`](https://github.com/termsurf/worm.note)                                                | **The BaseNote Content Grammar Library**                                                                                                                                                                                                                                                                                                                                                                   |
| <a href="https://github.com/termsurf/worm.note"><img src='https://github.com/termsurf/worm.note/blob/make/view/view.svg?raw=true' width='128'></a> | This is a collection of "grammars", written in [`note`](https://github.com/termsurf/link). These are pattern recognizers for generating object structures out of text or binary strings, and doing the reverse, of generating text/binaries from objects. They are defined in a language agnostic way.                                                                                                     |
|                                                [`seed.note`](https://github.com/termsurf/seed.note)                                                | **The BaseNote Math Library**                                                                                                                                                                                                                                                                                                                                                                              |
| <a href="https://github.com/termsurf/seed.note"><img src='https://github.com/termsurf/seed.note/blob/make/view/seed.svg?raw=true' width='128'></a> | This is a collection of mathematical formalizations, written in [`note`](https://github.com/termsurf/link). These are going to be used, following along the lines of the HoTT project, as a foundational model of mathematics for use in a programming environment.                                                                                                                                        |

<br/>
<br/>

We are just beginning, so _much_ work is being done on the specifications, with only rough prototype implementations to test out the specifications. Once we finish the specifications and base implementations, it should be a usable cross-platform environment. Please reach out to use by opening an issue in any of the projects or finding us on Twitter if you'd like to discuss, exchange ideas, or in other ways join in the fun.

## Language Building

Like mentioned, [`tune`](https://tune.surf) is a language we derived from imagining an ancient stone-tool making monkey culture of the past, and evolved it into a modern language capable of representing all of modern concepts and knowledge, such as naming species and places and everything you can imagine. That is very much an evolving work-in-progress.

We also created [`tone`](https://tone.surf), a writing system for the languages of Earth. It is used in `tune` as the standard writing system as well.

<p align='center'><img src='https://github.com/termsurf/.github/blob/make/view/stream.svg?raw=true' height='512'></a></p>
