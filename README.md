# awesome-go-linters

This is a list of Go linters not available in [golangci-lint] but that can be useful to add to your projects.

## Architecture

- [go-arch-lint](https://github.com/fe3dback/go-arch-lint): GoLang architecture linter (checker) tool. Will check all project import path and compare with arch rules defined in yml file.

## Code Consistency

- [godddlint](https://github.com/manuelarte/godddlint): ![Static Badge][golangci-plugin] Go Linter 🧐 that checks domain structs honor best practices.
- [requiredfield](https://github.com/abhinav/requiredfield): Go linter that checks for required fields in structs.
- [structinit](https://github.com/manuelarte/structinit): ![Static Badge][golangci-plugin] Go Linter 🧐 to ensure struct's field initialisation order matches struct's field declaration.

## Testing

- [go-triple-a-lint](https://github.com/survivorbat/go-triplea-lint): This linter aims to enforce the use of `Arrange/Act/Assert` or `Given/When/Then` comments in tests.
- [testcomments](https://github.com/manuelarte/testcomments): ![Static Badge][golangci-plugin] Go Linter that follows standards described in [TestComments](https://go.dev/wiki/TestComments).

[golangci-lint]: https://golangci-lint.run
[golangci-plugin]: ![Static Badge](https://img.shields.io/badge/golangci-plugin-blue)

