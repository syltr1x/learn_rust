## Variables Types
### String (and chars) types
* char: only contain one character can be interpreted by UTF-8. 
```rust 
let char_one: char = 'E';
```
* &str: inmutable string type, used to store slice of string without copying
```rust
let mut string_one = "example text"; // this no make sense because is a &str type (can't mutate)
```
* String: mutable string type
```rust
let mut greeting = String::from("hi world!");
greeting = String::from("bye world!"); // ✅ Change the value of greeting to "bye world!" (formatted to String)
greeting = "goodbye!"; // ❌ This tries to reasign greeting type to &str
```
### Integer types
#### i -> integers (- and +)
* i8   -> from -128 to 127
* i16  -> from -32768 to 32767
* i32  -> from -2147483648 to 2147483647
* i64  -> from -9223372036854775808 to 9223372036854775807
* i128 -> from -170141183460469231731687303715884105728 to 170141183460469231731687303715884105727

#### u -> unasigned sign (only positives)
* from 0 to:
* u8   -> 255 
* u16  -> 65535
* u32  -> 4294967296
* u64  -> 18446744073709551615
* u128 -> 340282366920938463463374607431768211455

## Projects
* [Calculator](https://github.com/syltr1x/learn_rust/main/blob/calc/main.rs)
* [Emoji Selector](https://github.com/syltr1x/learn_rust/main/blob/emoji_sel/main.rs)
