# riscv-k-spec
Working draft of the proposed RISC-V K quantum extension

The top level file is [k-spec.adoc](./k-spec.adoc)

Simply clicking on the file in the github repo viewer will render a usable
version as markdown.

For a better rendering, use "asciidoctor k-spec.adoc".

This work is licensed under a Creative Commons Zero v1.0
Universal License. See the LICENSE file for details.

[[HTML](https://openql-org.github.io/documents/riscv-k-spec/)] [[PDF](https://opqnel-org.github.io/documents/riscv-k-spec/riscv-k-spec.pdf)]

### Additional Resources

- The [Binutils for K extension 0.0.1](https://github.com/openql-org/riscv-binutils-gdb)
- The [GNU Compiler Collection for K extension 0.0.1](https://github.com/openql-org/riscv-gcc) with [GNU toolchain](https://github.com/riscv/riscv-gnu-toolchain)
- The [Spike simulator](https://github.com/openql-org/riscv-isa-sim)
  (to be used with e.g. Spike) supports enabling QUP support
  when compiled with a K extension capable GNU toolchain

### Documentation generator

Requirements

`node v6+`

**Linux**: install using [nvm](https://github.com/creationix/nvm)

**OSX**: `brew install node`

**Windows**: [nodejs.org](https://nodejs.org/en/download/)

Install documentation generator

`npm i`

Build HTML/PDF documents

`npm run build`

Resulted files

`public/*`
