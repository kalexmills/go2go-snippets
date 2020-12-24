# Go2Go Snippets

To better understand the impact of the Go generics proposal, this repository collects a list of solutions to [problems that could benefit from generics] that run on the [go2go Playground](https://go2goplay.golang.org/p/rC4sofqXuA5). Pull requests are welcome! Just include a `main` method that demonstrates correct usage.

Multiple implementations are encouraged. Having a variety of solutions to look at and compare will help the community learn about idioms that may be useful.

## Data structures

### Queue
FIFO access to a list.

* enqueue and dequeue (standard example) ([go2go](https://go2goplay.golang.org/p/WU9wGGNraGB))

### Graph
Data structure consisting of nodes and edges.

## Algorithms

### Min / Max
Find smallest/largest element in slice.

### Average / Standard Deviation
Find average/standard deviation of slice.

### Union / Intersection
Compute union/intersection of maps.

### Shortest Path
Find shortest path in node/edge graphs.

### `map` over Collections
Apply an arbitrary transformation function to slice/map, returning new slice/map.

### Channel timeout
Read from a channel with a timeout.

### Join channels
Combine two channels into a single channel.

### Parallel `map`
Call a list of functions in parallel, returning a slice of results.

### Parallel `oneOf` 
Call a list of functions using a Context, return the result of the first function to finish, while canceling and cleaning up extra goroutines.
