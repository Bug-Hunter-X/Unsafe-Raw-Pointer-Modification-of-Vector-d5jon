# Unsafe Raw Pointer Modification of a Vector in Rust

This repository demonstrates a common error in Rust: using raw pointers to modify a vector's contents without proper care. This practice can lead to undefined behavior, crashes, or subtle data corruption if not handled correctly.

The `bug.rs` file shows the erroneous code, while `bugSolution.rs` provides a safer and more idiomatic alternative using Rust's safe memory management features.

This example highlights the importance of avoiding unsafe operations whenever possible and leveraging Rust's built-in safety features for memory management.  Always prioritize safe, idiomatic code over manual memory management unless absolutely necessary and you fully understand the implications.