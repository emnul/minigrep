# minigrep

A simple grep implementation in Rust. I created this project to familiarize myself with some core Rust features such as:

- Error Handling
- I/O
- Environment Variables
- Writing Tests
- Traits and Lifetimes
- Common Collections such as Vec and String
- Modules
- Iterators and Closures

## Usage

Clone this repo and add the .txt file that you want to search to the project's root directory.

Run `cargo run -- <query_string> <file_name.txt>` for case sensitive search

Run `IGNORE_CASE=1 cargo run -- <query_string> <file_name.txt>` for case insensitive search
