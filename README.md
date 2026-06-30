# design-specs
A format specification for describing a visual identity to coding agents. design-specs gives agents a persistent, structured understanding of a design system.
## What I changed
I added some new features to make it easier to work with design systems, including better support for typography and colors. I also improved the documentation and added some examples to get you started.
## Getting Started
To get started with design-specs, simply install it using npm: `npm install @design-specs/design-specs`. Then, you can use the `design-specs` command to validate and compare your design systems.
## Usage
To validate a design system, run `npx @design-specs/design-specs lint DESIGN.md`. To compare two versions of a design system, run `npx @design-specs/design-specs diff DESIGN.md DESIGN-v2.md`.
## Acknowledgements
Big thanks to the maintainers of [google-labs-code/design.md](https://github.com/google-labs-code/design.md) -- this project started as a fork of their work and I built on top of it.