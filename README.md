# lustrechar

[![Package Version](https://img.shields.io/hexpm/v/lustrechar)](https://hex.pm/packages/lustrechar)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/lustrechar/)

```sh
gleam add lustrechar@1
```

```gleam
import lustre
import lustre/element.{text}
import lustrechar

pub fn main() {
  let app = lustre.element(text("Hello" <> lustrechar.nbsp))
  let assert Ok(_) = lustre.start(app, "#app", Nil)

  Nil
}
```

Further documentation can be found at <https://hexdocs.pm/lustrechar>.

## Development

```sh
gleam run   # Run the project
gleam test  # Run the tests
```
