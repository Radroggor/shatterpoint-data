# Shatterpoint Data 2

An easy-to-use collection of all data from [Star Wars: Shatterpoint](https://www.atomicmassgames.com/shatterpoint/) by [Atomic Mass Games](https://www.atomicmassgames.com/).

## SPT ids

Every unit, ability, era, etc. has a `spt` field that contains a unique id.

New SPT ids are generated using the following steps:

1. Take the English-language name as printed on the card
1. Lowercase the name
1. Convert non-ASCII characters to closest ASCII equivalent (to remove umlauts, etc.)
1. Remove non-alphanumeric characters

SPT ids have to be unique per type (unit/ability/era/etc).

## Creating a pull request

Before opening a pull request, see the following checklist:

1. Use sensible commit messages. Good: `add Han Solo units`. Bad: `create fang-fighter.json`
1. Ensure there are no merge conflicts with `master` (rebase on top of `master` or merge it into your branch)
1. Use a sensible PR message, eg `add new era`. PR messages can be the same as commit messages for single-commit PRs.

## Versioning

This project uses [SemVer](http://semver.org/). Given a `MAJOR.MINOR.PATCH` version number, we will increment the:

- `MAJOR` version when existing content is changed in such a way that it can break consumers of the data
- `MINOR` version when new content is added in a backwards-compatible manner, or existing content is changed in a backwards-compatible manner
- `PATCH` version when fixing mistakes in existing content

## History

See the [Releases tab](https://github.com/Radroggor/shatterpoint-data/releases) in Github.

## License

[GNU GPL](LICENSE)

---

Star Wars: Shatterpoint and all related properties, images and text are owned by Atomic Mass Games, Lucasfilm Ltd., and/or Disney.
