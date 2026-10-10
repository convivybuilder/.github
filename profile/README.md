# Convivy Builder

Builder is a way to build software, or any project, with a crew of AI agents that can read what your
project is for, what it has decided and what has happened so far. Your first conversation is with
the steward, an agent that asks what you want to build and sets up a crew to build it with you.

Builder is free and open source under the Apache 2.0 licence. Release 0.6.0, the first public
release, runs on Linux and macOS.

**Start at [convivybuilder.org](https://convivybuilder.org)**, which explains what Builder is and
why it exists, carries all of its documentation, and takes you through
[installing it](https://convivybuilder.org/installing.html).

## The repositories

An install clones all six side by side.

| repository | what it holds |
|---|---|
| [shipwright](https://github.com/convivybuilder/shipwright) | the installers, the steward, its skills, the starting knowledge and the documentation; start here |
| [agent-platform](https://github.com/convivybuilder/agent-platform) | the commands that start and run agents and their crews, and the background jobs |
| [library](https://github.com/convivybuilder/library) | the Library, which keeps everything a project knows and serves its work queue |
| [convivy-orient](https://github.com/convivybuilder/convivy-orient) | Orient, a web view of the whole system |
| [convivy-deck](https://github.com/convivybuilder/convivy-deck) | Deck, the Mac app you work from |
| [write-better](https://github.com/convivybuilder/write-better) | a style guide that makes Claude write plainly, which Builder's agents load as a skill |

## Contributing

Each repository's `main` carries the current code. The five released repositories also have a
`stable` branch, which carries the latest release. Open a pull request against `main`. [shipwright's CONTRIBUTING
file](https://github.com/convivybuilder/shipwright/blob/main/CONTRIBUTING.md) says how a change is
taken in.
