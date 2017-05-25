# historian changelog

## 0.1.0

* Use /usr/bin/env bash instead of /bin/bash

* Remove subshell invocations from sqlite queries

* Declare variables as read-only, etc. as appropriate

* Always clean up temporary files on exit (on hist import)

* hist search now can search for multiple terms at once

* Simplify sub-command invocation

* Code now passes shellcheck

## 0.0.2

* Renames global variables to `HISTORIAN_SRC`, `HISTORIAN_DB`,
  `HISTORIAN_SQLITE3` and makes them overridable from outside the
  script

* Fixes import delimiter bug to allow for backtick (but disallow 0x01)

## 0.0.1

* Initial implementation
