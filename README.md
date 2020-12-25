# Go2Go Snippets

To better understand the impact of the Go generics proposal, this repository collects a list of solutions to problems that could benefit from generics and links to implementations that run on [The go2go Playground](https://go2goplay.golang.org). Multiple implementations for the same problem are highly encouraged. Having a variety of solutions to look at and compare will help the community learn about approaches to generics that may and may not be useful.

If you are copying from an online source, please make sure 1) you are able to do so and 2) include a link back to the original material.

Pull requests are welcome, both for solutions to the problems below and solutions of new problems! Just modify this file to a link to a go2go example that includes a `main` method demonstrating correct usage. Maintainers may run format on your submission and modify the link before merging, but we *will* preserve your original commit in the history.

If you see an implementation in this list that you have questions about or want to discuss, start a conversation in the issue tracker. Please follow the [Go Community Code of Conduct](https://golang.org/conduct).

### Data structures

 * **Queue**: FIFO access to a list
    * enqueue and dequeue (standard example) ([go2go](https://go2goplay.golang.org/p/WU9wGGNraGB))

### Algorithms

 * **Min/Max**: find smallest/largest element in a collection
    * using a numeric interface ([go2go](https://go2goplay.golang.org/p/-SpQWxkaubc))
 * **Reverse**: reverse an ordered collection
    * example from 'Why Generics' ([go2go](https://go2goplay.golang.org/p/birTLemLU3l), [source](https://blog.golang.org/why-generics))
 * **Union/Intersection**: perform basic set theory
    * using 'sets' -- maps with empty structs for values ([go2go](https://go2goplay.golang.org/p/8D4zmkrUkkK))
* **Transform Collections**: apply a function to each element of a collection and return the resulting collection.
   * mapping over slices ([go2go](https://go2goplay.golang.org/p/5fxKKfXYCMK))
 * **Average/Standard Deviation**: compute statistical moments of a collection
    * *TODO*
 * **Shortest Path**: find shortest path in a graph
    * *TODO*
   
### Concurrency

 * **Channel Join**: combine two channels into one
    * async implementation ([go2go](https://go2goplay.golang.org/p/BdAT9Htwr0_K))
 * **Parallel `allOf`**: call a list of functions in parallel, returning a slice of results
    * retrieve response code from parallel HTTP requests ([go2go](https://go2goplay.golang.org/p/aXjp9q54d_5))
 * **Parallel `oneOf`**: call a list of functions in parallel, return the fisrt function to finish, cancelling the remainder and not leaking any goroutines.
    * *TODO*
 * **Channel Timeout**: read from a channel with a timeout
   * *TODO*
