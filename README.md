# mypy pre-commit hook

pre-commit hook of mypy with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For mypy: see [here](https://github.com/python/mypy)

## Using mypy with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-mypy
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: mypy-conda
```
