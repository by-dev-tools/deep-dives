# deep-dives

Interactive design sessions for Claude Code. Each skill takes one designer's
approach and runs it as a working session: Claude facilitates, sketches and
pushes, and **you make every call**.

deep-dives is for **incubating ideas**, not shipping production code. Sketches
are throwaway, turns are short, and there's no setup. Its sibling plugin,
[flow](https://github.com/by-dev-tools/flow), is the opposite: it automates the
path from an approved plan to a merged PR. They can be installed separately or
together.

## Skills

| Skill | What the session does | Inspired by |
|---|---|---|
| `/deep-dives:puckett-uncommon-care` | Pushes **one interaction** from functional to cared-for. Claude maps the obvious version, builds rough live sketches with tuning sliders, and reads them through eight lenses. You touch each sketch, choose one, and take it deeper. The tuned values are what you keep. | Josh Puckett |

`/deep-dives:yuan-brand`, a session for building a brand from a human truth
outward (inspired by Jason Yuan), is in development and will land here next.

Each skill runs only when you invoke it. Its approach is written down in its
own `references/doctrine.md`, and the skill cites that file as it goes.

## Install

deep-dives is listed in the `flow` marketplace:

```
/plugin marketplace add by-dev-tools/flow
/plugin install deep-dives@flow
```

You don't need to use flow to use deep-dives. To try a local checkout instead:
`claude --plugin-dir /path/to/deep-dives`.

## Where the ideas come from

These skills are built on other people's thinking, and we'd rather say so
plainly than leave you to guess.

- **Josh Puckett: uncommon care.** The idea of executing limited scope to an
  extraordinarily high bar comes from Josh's conversation on Dive Club,
  [*Crafting interfaces with uncommon care*](https://www.youtube.com/watch?v=wym3V9FycTk)
  (2026). Josh teaches this properly in his own library,
  [Interface Craft](https://www.interfacecraft.dev). If the skill is useful to
  you, that's where to go next.
- **Jason Yuan: thoughtful brands.** The brand session, once it lands, draws on
  Jason's Dive Club conversation,
  [*Designing 99 "No"s for a single "Yes"*](https://www.youtube.com/watch?v=qsuqgj4tn0k)
  (2026).

Each skill's `references/doctrine.md` is **our own reading** of those
conversations, partly written with AI help and not checked against a
transcript. It isn't a summary either designer wrote or approved, and it
borrows nothing from their paid material. Where a doctrine quotes, it says
whether the quote comes from the audio or from a third-party summary. Thanks
also to [Dive Club](https://www.youtube.com/@joindiveclub) for the interviews.

deep-dives is an independent project. It is not affiliated with or endorsed
by Josh Puckett, Jason Yuan or Dive Club.

## License

MIT. See [LICENSE](LICENSE). The license covers this repository's own text and
files, not the ideas or work of the people credited above.
