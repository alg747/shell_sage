# Release Notes

<!-- do not remove -->

## 0.0.9


### Bugs Squashed

- Initial use after install errors looking for: fastlite ([#41](https://github.com/AnswerDotAI/shell_sage/issues/41))


## 0.0.8

### New Features

- Add logging of queries and response to Sqlite #27 ([#32](https://github.com/AnswerDotAI/shell_sage/pull/32)), thanks to [@aditya0yadav](https://github.com/aditya0yadav)

### Bugs Squashed

- Fix: Handle invalid/empty tmux history-limit values ([#39](https://github.com/AnswerDotAI/shell_sage/pull/39)), thanks to [@nassersala](https://github.com/nassersala)
  - ### **Fix: Handle invalid/empty `tmux history-limit` values**  

## 0.0.7

### New Features

- Add version flag to cli ([#28](https://github.com/AnswerDotAI/shell_sage/issues/28))

### Bugs Squashed

- base_url error when user updates shell sage to new version with different config schema ([#22](https://github.com/AnswerDotAI/shell_sage/issues/22))

- command mode not working outside tmux session ([#21](https://github.com/AnswerDotAI/shell_sage/issues/21))

- tmux scrollback history does not check tmux session is active ([#20](https://github.com/AnswerDotAI/shell_sage/issues/20))


## 0.0.6

### New Features

- Make inserting commands in the command line frictionless ([#17](https://github.com/AnswerDotAI/shell_sage/issues/17))

- Add link to pygments for theme and lexer configuration ([#16](https://github.com/AnswerDotAI/shell_sage/issues/16))

- Add Support for OpenAI Compatible Providers ([#12](https://github.com/AnswerDotAI/shell_sage/issues/12))

### Bugs Squashed

- Having inline comments in config causes errors ([#18](https://github.com/AnswerDotAI/shell_sage/issues/18))

- TypeError: option values must be strings when starting with fresh config ([#15](https://github.com/AnswerDotAI/shell_sage/issues/15))


## 0.0.5


### Bugs Squashed

- ShellSage Not Seeing Full Tmux History ([#11](https://github.com/AnswerDotAI/shell_sage/issues/11))

### Features Added

- Add configuration through ~/.config/shell_sage/shell_sage.conf file
- Default history length to tmux's scrollback history 
- Add system info to prompt

## 0.0.4

- Add support for OpenAI models
- Remove action mode
- Add ability to configure shell sage with a configuration file


## 0.0.3



