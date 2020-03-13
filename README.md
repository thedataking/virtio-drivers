# VirtIO-drivers-rs

[![CI](https://github.com/rcore-os/virtio-drivers/workflows/CI/badge.svg?branch=master)](https://github.com/rcore-os/virtio-drivers/actions)

VirtIO guest drivers in Rust. For **no_std + no_alloc** environment.

🚧 Working In Progress. We are now moving code from [rCore kernel](https://github.com/rcore-os/rCore/tree/master/kernel/src/drivers) to here.

## Components

| Module | Status                                                       |
| ------ | ------------------------------------------------------------ |
| Queue  | ✅                                                            |
| Block  | ✅                                                            |
| Net    | 🚧 [TODO](https://github.com/rcore-os/rCore/blob/master/kernel/src/drivers/net/virtio_net.rs) |
| GPU    | ⚠️ Not tested                                                 |
| Input  | 🚧 [TODO](https://github.com/rcore-os/rCore/blob/master/kernel/src/drivers/input/virtio_input.rs) |
| ...    | ❌ Not implemented                                            |

## Examples & Tests

* x86_64 (TODO)

* [RISCV](./examples/riscv)
