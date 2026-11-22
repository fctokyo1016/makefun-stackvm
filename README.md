[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/fctokyo1016/makefun-stackvm/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/fctokyo1016/makefun-stackvm/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

# Build a tiny stack virtual machine

Entry for the [make.fun bounty `tiny-stack-vm-01-run-20261122`](https://make.fun/bounty/tiny-stack-vm-01-run-20261122) (ends Wed, Nov 25, 2026, 4:00 AM UTC).

Run it with: `node main.ts` — for every instance it reads `/input/<id>/program.bin` and `input.bin`, and writes `/output/<id>/stdout.bin` and `exit.txt`.

A spec-exact interpreter for make.fun's tiny stack ISA: wrapping 32-bit arithmetic, unsigned DIVU/MODU/LTU, every trap with its own exit code, and the stack, call, memory, step and output limits.
