# balanced_tree_gleam

A Gleam friendly wrapper around erlang's `gb_trees` module

[![Package Version](https://img.shields.io/hexpm/v/balanced_tree_gleam)](https://hex.pm/packages/balanced_tree_gleam)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/balanced_tree_gleam/)

`balanced_tree` implements the same functions as `gleam/dict`, and some additional for folding and min/max related operations.

Build Target is Erlang-only. I may consider writing a javascript implementation in the future

WIP. Expect sudden API changes until 1.0.0

```sh
gleam add balanced_tree_gleam
```
```gleam
import balanced_tree

pub fn main() -> Nil {
  // TODO: An example of the project in use
}
```

Further documentation can be found at <https://hexdocs.pm/balanced_tree>.

## Development

```sh
gleam run   # Run the project
gleam test  # Run the tests
```
