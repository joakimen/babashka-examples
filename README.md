# babashka-examples

Samples of useful things to do in Clojure that are supported by the [babashka](https://github.com/babashka/babashka)-interpreter.

## Ideas

- [x] Implementing protocols (interfaces) with `clojure.core.protocols`
- [x] CLI argument parsing with `babashka.cli`
- [x] Logging with `timbre`
- [x] Pattern matching with `clojure.core.match`
- [ ] Using the babashka CLI as a [Task Runner](https://book.babashka.org/#tasks) to replace Makefiles
- [x] HTTP client using `slurp`, `org.httpkit.client`, `babashka.curl` etc
- [x] Property testing with `clojure.test.check`
- [ ] Glueing together CLI-utilities with `process`
- [ ] Wait for ports/files with `babashka.wait`
- [ ] Parse data
  - [ ] JSON with `cheshire.core`
  - [ ] YAML with `clj-yaml.core`
- [ ] File system operations using `babashka.fs`
- [x] Multi-method polymorphism

## See also

- [Babashka book](https://book.babashka.org) - Documentation and code examples
- [Babashka toolbox](https://babashka.org/toolbox) - Overview of builtin and third-party libraries
