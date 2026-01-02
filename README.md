# html-builder

A minimal, zero-dependency, `no_std` HTML5 library for Rust following the
[WHATWG HTML Living Standard](https://html.spec.whatwg.org/).

## Crates

| Crate                                     | Description                                                              |
| ----------------------------------------- | ------------------------------------------------------------------------ |
| [html-builder](crates/html-builder)       | Core HTML builder with type-safe element construction and XSS protection |
| [html-elements](crates/html-elements)     | All 110+ HTML5 elements as zero-sized types with content category traits |
| [html-attributes](crates/html-attributes) | Typed attributes (global + element-specific) with validation             |
| [html-macro](crates/html-macro)           | Proc-macro for ergonomic HTML generation with Rust-like syntax           |
| [html-parser](crates/html-parser)         | HTML5 parser and validator following WHATWG spec                         |

## Features

- Zero dependencies (only uses `alloc`)
- `no_std` compatible, builds to WebAssembly
- Type-safe builder pattern with compile-time validation
- Automatic XSS protection via HTML/attribute escaping
- Complete HTML5 element and attribute coverage

## Documentation

See the
[API documentation](https://leakix.github.io/html-builder/html_builder/).

## License

MIT
