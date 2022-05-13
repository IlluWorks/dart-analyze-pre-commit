# Dart Analyze `pre-commit`

[`pre-commit`](https://pre-commit.com) hook for running Dart anlyzer

Add the following in your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/merely-agile/dart-analyze-pre-commit
  rev: "main"
  hooks:
    - id: dart-analyze
```

## Acknowledgements

[Charles Crete](https://github.com/Cretezy/) for creating `flutter-format-pre-commit`

[Dariusz Łuksza](https://github.com/dluksza) for creating `flutter-analyze-pre-commit`
