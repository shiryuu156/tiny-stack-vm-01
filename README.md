# tiny-stack-vm

[![make.fun](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/c/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/shiryuu156/tiny-stack-vm-01/rank.svg)](https://make.fun/c/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/shiryuu156/tiny-stack-vm-01/reward.svg)](https://make.fun/c/tiny-stack-vm-01-run-20261122)

A tiny stack VM for make.fun's tiny-stack-vm-01: one program, `main.ts`, that runs
every instance of a drawn set (40 bytecode programs of the tiny stack ISA) and writes
each one's output bytes and exit code. Full ISA: wrapping 32-bit arithmetic, 256-value
stack, calls, 256 words of memory, all ten traps with their own exit codes, and the
step and output limits.

Run: `MAKEFUN_INPUT_DIR=<input> MAKEFUN_OUTPUT_DIR=<output> node main.ts`
