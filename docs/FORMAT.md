# Formatting Guidelines

All files should adhere to these formatting guidelines.

## Shell Script Formatting

- All `build.sh` should be set to `644` permission.

- All scripts should use tabs rather than spaces.

- All parantheses of shell functions should not be preceded with a space.

- Avoid use of non utf-8 encoding.

- Comments should be compact. Do not tab them if not necessary.

## Shell Script Coding Practices

- Dollar parentheses `$()` rather than backticks ``` `` ``` should be employed in command substitution.

- `install` is preferred over `cp` as the installation program.

- Version numbers should never be hard-coded. Instead, use the `$TERMUX_PKG_VERSION` and `$TERMUX_PKG_REVISION` variables.

## Markdown Formatting

- All `filenames` should be under code formatting, unless they are links.

- All titles should be indented with hashes rather than equal signs.

- All unnumbered lists should be indented with hyphens. 

- All Markdown should be edited on alternate line.

- All Markdown should use tabs rather than spaces.

- All `.md` should be set to `644` permission.

- All characters should be escaped.

- All names of `.md` should be capitalised.

- All code blocks should be enclosed in backticks, with language specified.