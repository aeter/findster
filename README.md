### findster

A fast text searching tool with focus on simplicity.<br />
Usage: ```./fe <regex> <dir>```

- Features
  - [x] searching with regex patterns
  - [x] search the dir recursively by default
  - [x] search in pwd when no dir is specified
  - [x] handle colour if stdout is piped/tty
  - [x] ignore searching ".git" dirs (annoying)
  - [x] search stdin when piped
  - [x] if called as ```./fe <regex> <file>```, search the file
  - [x] ignore searching binary files
