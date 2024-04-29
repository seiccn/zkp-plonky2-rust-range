
## Introduction to Plonky2

PLONK2 is designed to provide efficient and scalable ZKPs for a wide range of applications, including blockchain, privacy-preserving computation, and secure multiparty computation. It achieves this by leveraging techniques such as polynomial commitments, polynomial interpolation, and permutation arguments.

One of the key features of PLONK2 is its ability to support large-scale computations with high efficiency, making it suitable for complex and resource-intensive applications. It achieves this efficiency through techniques like polynomial commitment schemes and the use of universal and updatable structured reference strings.

## How to Build and Run

Make sure you have Rust installed on your system. If not, you can install it using [rustup](https://rustup.rs/).

To execute the project, navigate to its directory in your terminal and enter the following command:

```
rustup override set nightly
RUSTFLAGS=-Ctarget-cpu=native cargo run --release -- -vv
```

## Implementation Details

An example of using Plonky2 to prove that a given value lies in a given range.
