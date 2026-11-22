# Tiny Stack VM

[![tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/competitions/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/yuniasandria/tiny-stack-vm-01/rank.svg)](https://make.fun/competitions/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/yuniasandria/tiny-stack-vm-01/reward.svg)](https://make.fun/competitions/tiny-stack-vm-01-run-20261122)

An exact interpreter of make.fun's tiny stack ISA v1, written in plain
JavaScript (Node 22 stdlib only, no dependencies). For every program in the
input directory it runs the reference semantics — all 36 opcodes, wrapping
32-bit arithmetic, unsigned DIVU/MODU/LTU, the 1,000,000-step and 65,536-byte
output limits, and all 11 trap codes with their exact exit codes — and writes
the program's stdout and exit code.

Run it with:

```sh
MAKEFUN_INPUT_DIR=<input dir> MAKEFUN_OUTPUT_DIR=<output dir> node main.ts
```

Referral code: `6cmdpsm5`
