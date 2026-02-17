# A clang-format action

This action checks the formatting of a project with respect to `clang-format`.
It is heavily based on https://github.com/jidicula/clang-format-action, and only
exists as a temporary replacement whilst that action is failing.

## Inputs

- clang-format-version [optional]: The major version of clang-format that you want to run on your codebase.
  - Default: `21`
- check-path [optional]: The path to the directory in the repo that should be checked for C/C++/Protobuf formatting.
  - Default: `.`
- exclude-regex [optional]: A regex to exclude files or directories that should not be checked.
  - Default: `^$`
