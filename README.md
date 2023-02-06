# Generics in method definitions

This tiny anecdotal example from the [Rust book](https://doc.rust-lang.org/book/ch10-01-syntax.html#in-method-definitions)
highlights the fact that (we quote) "Generic type parameters in a struct definition aren’t always
the same as those you use in that same struct’s method signatures."

Method `mixup` in the [impl Point](src/main.rs) "creates a new Point instance with the x value from
the self Point (of type X1) and the y value from the passed-in Point (of type Y2)."