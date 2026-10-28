# MicroOS
A minimal x86_64 kernel written in Rust. Boots in QEMU and prints text via VGA.

## Run
cargo run   (requires QEMU, bootimage 0.10.3, nightly-2025-06-01)

## Notes
- Toolchain pinned in rust-toolchain.toml
- bootloader 0.9.35's x86_64-bootloader.json needed manual edits
  (target-pointer-width and target-c-int-width as strings, rustc-abi = "x86-softfloat")

## Aim:
-to build a completely working micro operating system that runs virtually by the end of semester 3
