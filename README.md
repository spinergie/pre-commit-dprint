dprint pre-commit mirror
========================

*Adopted from https://github.com/adamchainz/pre-commit-dprint. Thanks to [@adamchainz](git@github.com:spinergie/pre-commit-dprint.git) for their work!*

----

Mirror of [dprint](https://dprint.dev/) for [pre-commit](https://pre-commit.com).

Installation
------------

Add to your pre-commit config:

```yaml
-   repo: https://github.com/adamchainz/pre-commit-dprint
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: dprint
```

Then add a `dprint.json` (or `.dprint.json`) [configuration file](https://dprint.dev/config/) in the root of your repository.

By default all text files are passed to dprint, which then only acts on files for which it has a relevant plugin configured.
