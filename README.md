# lint_example
<img src="cover.png">

Use a code analyzer to check what we type. Keep the project of good quality and avoid some issues. The packages <b>flutter_lint</b> or <b>lint</b> are all good. Depends on you or your team.

## Packages

- [lint](https://pub.dev/packages/lint)
- [dart_code_metrics](https://pub.dev/packages/dart_code_metrics)

### Analyze

```bash
flutter pub run dart_code_metrics:metrics analyze lib
```

### Check unused files

```bash
flutter pub run dart_code_metrics:metrics check-unused-files lib
```

### Check unused code

```bash
flutter pub run dart_code_metrics:metrics check-unused-code lib
```
