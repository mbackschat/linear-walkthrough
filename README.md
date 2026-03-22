# linear-walkthrough

A Claude Code skill that creates detailed linear walkthroughs of codebases using [showboat](https://github.com/simonw/showboat).

## Installation

Copy the `.claude/skills/linear-walkthrough/` directory into your project or personal `~/.claude/skills/` directory.

## Usage

```
/linear-walkthrough [path-to-source]
```

## Prerequisites

- [Claude Code](https://claude.com/claude-code) CLI
- [showboat](https://github.com/simonw/showboat) installed and available in PATH

## TODO

- [ ] Once [showboat#25](https://github.com/simonw/showboat/pull/25) lands (`--output-lang` flag), remove the manual fence-fixing step from the skill and use `--output-lang` instead.

## Credits

Based on the [Linear Walkthroughs](https://simonwillison.net/guides/agentic-engineering-patterns/linear-walkthroughs) pattern from Simon Willison's Agentic Engineering Patterns guide.
