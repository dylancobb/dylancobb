I’m Dylan, a software developer and musician with a persistent curiosity for how things work. I enjoy exploring the intersection between code, maths, and sound—often building musical tools in my spare time—and I’m always learning, experimenting, and collaborating with others along the way.

![banner](https://dylancobb.dev/img/og.png)

Some recent side projects:
- [Meantonal](https://meantonal.org/), an open source library for representing musical pitch in a *semantically non-destructive* way, using linear algebra to make operations that are challenging to achieve with other libraries trivial. I wrote both a C and a TypeScript implementation, making it suitable in desktop, web, or even embedded musical applications.
- [A melody and counterpoint generator](https://cantussy.com/), which uses both the C and TypeScript versions of Meantonal to wrangle and render pitches, and Verovio for score rendering and the Web Audio API for playback. The melody and counterpoint generation code is written in C and compiled to WASM, and called via JavaScript in the browser.
- (WIP) A [graphical text editor](https://github.com/dylancobb/text-editor) based on the architecture of Emacs and Neovim. Written as a cross-platform (including the browser via WASM) SDL3 application in C, with Chibi Scheme as the embedded interpreted language that will provide user configurability extensibility. The goal is for this to eventually evolve into the frontend for a music composition environment built around a plaintext markup language in the spirit of [LilyPond's](https://lilypond.org/). Things I'm interested in trying to implement for it:
  - Networked collaborative editing using sockets and [Eg-walker](https://arxiv.org/pdf/2409.14252).
  - Real-time score rendering that updates as the user types.
  - An audio rendering pipeline.

I've also been getting my hands dirty with electronics and embedded C, as I'm designing and prototyping a split ergonomic keyboard.

## Contact

- [Email](mailto:dylancobb92@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/dylan-cobb-411439277)
