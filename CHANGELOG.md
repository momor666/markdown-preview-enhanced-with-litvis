# CHANGELOG for `markdown-preview-enhanced-with-litvis`

## 0.6.1

*   Suggest installing dependencies of `linter-ui-default` too to reduce the number of clicks by user

## 0.6.0

*   Use `atom-package-deps` to prompt about installing `linter-ui-default`
*   Merge from upstream to use better config defaults

## 0.5.2-0.5.6

*   Fix path detection for elm binaries

## 0.5.1

*   Use a local copy of `elm` to avoid its setup via npm
*   use an OS-specific temp directory (`echo $TMPDIR`) instead of hard-coded `/tmp/literate-elm`

## 0.5.0

*   Upgrade `vega` to `3.3.1`, `vega-lite` to `2.4.0` and `vega-embed` to `3.7.2` ([shd101wyy/mume#65](https://github.com/shd101wyy/mume/pull/65)).
