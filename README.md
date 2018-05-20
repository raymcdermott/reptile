# REPtiLe server library

A Clojure server designed to expose a shared PREPL

## Usage

```bash
$ clj -Areptile 9090 some-shared-secret
```

## Plan

The first version will be considered feature complete once the server provides

- [X] Shared REPL state
- [X] Shared view of edits in real-time 
- [X] Shared REPL history
- [X] Authentication using shared secret
- [X] A demo for hosting a server on an AWS server
- [X] Dynamic addition of new libraries to the REPL
- [ ] Incremental feedback on long running REPL evaluations
- [ ] Cancel long running REPL evaluations
- [ ] Limit user count (2, 3, 4, etc...)
- [ ] Limit users based on user names (jane, joe, mary, etc...)
 
## Planned features

After the initial version these additional features are planned

- [ ] Choice of Java / node runtime REPLs

## Bugs / Feature Requests

Please open an issue on the repo

## License

Copyright © 2018 Ray McDermott

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
