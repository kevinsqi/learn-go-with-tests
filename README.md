# Learn Go with Tests

https://github.com/quii/learn-go-with-tests

## Sections

Sum:

- Use reflect.DeepEqual to compare arrays/slices

Repeat:

- Write benchmark test with `func BenchmarkFuncname(b *testing.B)`
- Run with `go test -bench=.`

[Wallet](https://github.com/quii/learn-go-with-tests/blob/master/pointers-and-errors.md):

- Use errcheck to detect what errors are not covered by tests

Map:

- Maps are reference types - so never initialize an empty map variable `var m map[string]string`. Instead initialize it or use make: `map[string]string{}` or `make(map[string]string)`
- [Constant errors with custom DictionaryErr type](https://github.com/quii/learn-go-with-tests/blob/master/maps.md#refactor-3)
