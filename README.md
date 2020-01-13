mypy(-conda) mirror
===================

Mirror of mypy for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For black: see https://github.com/python/mypy

### Using black with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-mypy
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: mypy-conda
```

