# Gonum Simple Graph

[![GoDoc Widget]][GoDoc] [![Go Report Card Widget]][Go Report Card]

[GoDoc]: https://godoc.org/github.com/paralin/gonum-simple-graph
[GoDoc Widget]: https://godoc.org/github.com/paralin/gonum-simple-graph?status.svg
[Go Report Card Widget]: https://goreportcard.com/badge/github.com/paralin/gonum-simple-graph
[Go Report Card]: https://goreportcard.com/report/github.com/paralin/gonum-simple-graph

This is the gonum graph/simple package extracted to a separate module.

The goal is to reduce the weight of this dependency significantly if you only
need the basic graph functions.

Importing the graph/mat package significantly increases the binary size of this
package, so those imports have been excluded here.

## Upstream

Check out the [upstream project](https://github.com/gonum/gonum) as well.

## License

BSD-3
