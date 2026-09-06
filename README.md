# awesome-go-linters

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a list of Go linters not available in [golangci-lint] but that can be useful to add to your projects.

## Architecture

<!-- keep-sorted start -->
- [fe3dback/go-arch-lint](https://github.com/fe3dback/go-arch-lint): GoLang architecture linter (checker) tool. Will check all project import path and compare with arch rules defined in yml file.
<!-- keep-sorted end -->

## Code Consistency

<!-- keep-sorted start -->
- [abhinav/requiredfield](https://github.com/abhinav/requiredfield): Go linter that checks for required fields in structs.
- [manuelarte/godddlint](https://github.com/manuelarte/godddlint): ![Static Badge][golangci-plugin] Go Linter 🧐 that checks domain structs honor best practices.
- [manuelarte/structinit](https://github.com/manuelarte/structinit): ![Static Badge][golangci-plugin] Go Linter 🧐 to ensure struct's field initialisation order matches struct's field declaration.
<!-- keep-sorted end -->

## Testing

<!-- keep-sorted start -->
- [manuelarte/testcomments](https://github.com/manuelarte/testcomments): ![Static Badge][golangci-plugin] Go Linter that follows standards described in [TestComments](https://go.dev/wiki/TestComments).
- [survivorbat/go-triple-a-lint](https://github.com/survivorbat/go-triplea-lint): ![Static Badge][golangci-plugin] This linter aims to enforce the use of `Arrange/Act/Assert` or `Given/When/Then` comments in tests.
<!-- keep-sorted end -->

<!-- keep-sorted start -->
[golangci-lint]: https://golangci-lint.run
[golangci-plugin]: https://img.shields.io/badge/golangci-plugin-blue
<!-- keep-sorted end -->

