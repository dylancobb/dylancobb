I’m Dylan, a software developer and musician with a persistent curiosity for how things work. I enjoy exploring the intersection between code, maths, and sound—often building musical tools in my spare time—and I’m always learning, experimenting, and collaborating with others along the way.

![banner](https://dylancobb.dev/img/og.png)

My most recent side projects have been:
- An open-source library called [Meantonal](https://meantonal.org/) for representing musical pitch in a *semantically non-destructive* way, using linear algebra to make operations that are challenging to achieve with other libraries trivial. I wrote both a C and a TypeScript implementation, making it suitable in desktop, web, or even embedded musical applications.
- [A melody and counterpoint generator](https://cantussy.com/), which uses both the C and TypeScript versions of Meantonal to wrangle and render pitches, and [Verovio](https://verovio.org/) for score-rendering and the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) for playback. The melody and counterpoint generation code is written in C and compiled to WASM, and called via JavaScript in the browser.
- (WIP) A [graphical text editor](https://github.com/dylancobb/text-editor) based on the architecture of Emacs and Neovim. Written in C using [SDL3](https://libsdl.org/) for cross-platform rendering and input, [Clay](https://www.nicbarker.com/clay) for layout/UI, and [Chibi Scheme](https://synthcode.com/scheme/chibi/) as the embedded interpreted language that will provide user configurability extensibility. The goal is for this to eventually evolve into the frontend for a music composition environment built around a plaintext markup language in the spirit of [LilyPond's](https://lilypond.org/). Things I'm interested in trying to implement for it:
  - Networked collaborative editing using sockets and [Eg-walker](https://arxiv.org/pdf/2409.14252).
  - Real-time score rendering that updates as the user types.
  - An audio rendering pipeline.
- Getting my hands dirty with electronics and embedded C, as I've designed a split ergonomic keyboard and am in the process of prototyping it.

## Contact

- [Email](mailto:dylancobb92@gmail.com)
- [LinkedIn](www.linkedin.com/in/dylan-cobb-411439277)
