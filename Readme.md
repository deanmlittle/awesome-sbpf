# Awesome sBPF

A collection of awesome resources for learning sBPF Assembly (Solana eBPF). PRs welcome!

### Tooling:
- [sbpf](https://github.com/deanmlittle/sbpf) by @deanmlittle - a tool to quickly bootstrap, build, deploy and test sbpf assembly programs
- [ezbpf](https://github.com/deanmlittle/ezbpf) by @deanmlittle - a simply sBPF disassembler library with a CLI and WASM bindings

### Documentation
- [bpf.wtf opcodes](https://wayback-api.archive.org/web/20231004134038/https://bpf.wtf/sol-0x03-isa/) - a waybackmachine archive of Firedancer's [@riptl](https://github.com/riptl) old website explaining opcodes.
- [bpf.wtf syscalls](https://web.archive.org/web/20231004144333/https://bpf.wtf/sol-0x04-syscalls/) - a waybackmachine archive of Firedancer's [@riptl](https://github.com/riptl) old website explaining syscall APIs.
- [rbpf opcodes](https://github.com/solana-labs/rbpf/blob/main/src/ebpf.rs) - the opcodes of the ebpf library used in agave with inline documentation in code comments.
- [firedancer rbpf opcodes](https://github.com/firedancer-io/firedancer/blob/main/src/ballet/sbpf/fd_sbpf_opcodes.h) - the opcodes of sbpf used in firedancer's vm

### Rust Resources
- [sbpf-asm-macros](https://github.com/deanmlittle/sbpf-asm-macros) - some useful macros for inline ASM in rust to save CUs
- [sbpf-inline-asm](https://github.com/deanmlittle/sbpf-inline-asm) - an example of writing inline assembly in a Rust contract

### Smart contracts
- [TOKEN.sbpf](https://github.com/firedancer-io/token.sbpf) - a sample of a hand-rolled token contract
- [sbpf-asm-noop](https://github.com/deanmlittle/sbpf-asm-noop) - a bytecode optimal noop program with a custom linker file
- [sbpf-asm-slippage](https://github.com/deanmlittle/sbpf-asm-slippage) - a tiny slippage detection instruction in just 4CUs
- [solaba-fibonacci-asm](https://github.com/deanmlittle/solana-fibonacci-asm) - a fibonacci number solver written in sBPF ASM
