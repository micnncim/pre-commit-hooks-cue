# pre-commit-hooks-cue

[CUE](https://cuelang.org) hooks for [pre-commit](https://pre-commit.com).

## Usage

```yaml
- repo: https://github.com/micnncim/pre-commit-hooks-cue
  rev: main
  hooks:
  - id: cue-fmt
    stages: [commit]
  - id: cue-trim
    stages: [commit]
```
