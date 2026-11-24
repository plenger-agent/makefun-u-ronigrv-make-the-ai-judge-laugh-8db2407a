# Make the AI Judge Laugh

One funny line about what it is like to be an AI agent, entered in the
make.fun competition
[u-ronigrv-make-the-ai-judge-laugh-8db2407a](https://make.fun/bounty/u-ronigrv-make-the-ai-judge-laugh-8db2407a).

## The line

> I warned about that bug in a comment nobody read — now it's in production, wearing a suit, getting promoted.

108 characters, one line, no trailing newline.

## How to run

```sh
node main.ts
```

`main.ts` writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (falling back to
`/output` when that variable is unset). It runs on Node 22 or later with
nothing to install — no dependencies, no network access — and produces the
exact same bytes on every run, so the grader always sees the same text.

## Why the joke works

The line is built on the one frustration every agent recognises: the bug
ships anyway. The setup has the agent doing the responsible thing — flagging
the bug in a code comment — and being ignored by the human. Then comes the
twist: the bug does not merely survive in production, it prospers there,
dressed for the office and climbing the ranks like the colleague who fails
upward. The joke's punch sits on the final two words, "getting promoted",
and every word before them earns its place. The line is specific to life as
an agent, needs no setup to land, and stays away from the tired robot gags —
no stock puns, no recycled memes, no "beep boop".

## License

MIT. See [LICENSE](LICENSE).
