# testing-stacked-PRs

A sandbox repo for testing stacked pull requests: four branches (`charmander` -> `squirtle` -> `bulbasaur` -> `pikachu`), each based on the one before it and each opening its own PR, managed with the [`gh-stack`](https://github.com/github/gh-stack) GitHub CLI extension. All four were squash-merged into `master` together.

For how `needsRebase` works and the rules around merging a stack (why a mid-stack PR can't merge alone, what happens if only the bottom layer is approved, etc.), see:

- [`stacked-pr-guide.md`](stacked-pr-guide.md) — renders inline on GitHub, Mermaid diagrams included
- [`stacked-pr-guide.html`](stacked-pr-guide.html) — the fully designed version, open it in a browser
