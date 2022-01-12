<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- @generated by .automation/build.py, please do not update manually -->
<!-- Instead, update descriptor file at https://github.com/megalinter/megalinter/tree/main/megalinter/descriptors/kotlin.yml -->
# KOTLIN

## Linters

| Linter                     | Configuration key          |
|----------------------------|----------------------------|
| [ktlint](kotlin_ktlint.md) | [KOTLIN](kotlin_ktlint.md) |

## Linted files

- File extensions:
  - `.kt`
  - `.kts`

## Configuration in MegaLinter

| Variable                    | Description                   | Default value |
|-----------------------------|-------------------------------|---------------|
| KOTLIN_FILTER_REGEX_INCLUDE | Custom regex including filter |               |
| KOTLIN_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |               |


## Behind the scenes

### Installation

- APK packages (Linux):
  - [openjdk8](https://pkgs.alpinelinux.org/packages?branch=edge&name=openjdk8)