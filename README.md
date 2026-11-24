[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Gondok18-ui/tiny-stack-vm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Gondok18-ui/tiny-stack-vm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

# Tiny Stack VM

A faithful interpreter for make.fun's tiny stack ISA (v1): one TypeScript
file, Node 22 standard library only. For every program in the input directory
it writes exactly the bytes the program writes and the exit code it ends with.

- 32-bit wrapping arithmetic: exact low-32-bit multiply, signed and unsigned
  division and remainder, 5-bit shift counts, sign-extended PUSH8
- 256-deep data stack, 64-deep call stack, 256 words of memory
- All ten traps with their own exit codes, the 1,000,000-step limit and the
  65,536-byte output limit, every check in the spec's order

MIT licensed — see LICENSE.
