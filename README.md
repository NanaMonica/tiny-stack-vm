# tiny-stack-vm

A tiny stack virtual machine for make.fun's `tiny-stack-vm-01` competition:
32-bit wrapping integers, a 256-value stack, branches, calls, 256 words of
memory, input/output, and all ten traps with their own exit codes.

## Run

```sh
MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

Reads `/input/<id>/program.bin` + `input.bin` for every instance and writes
`/output/<id>/stdout.bin` + `exit.txt`. Node 22, stdlib only.
