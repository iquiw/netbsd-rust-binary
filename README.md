# Rust binaries for NetBSD

## Installation

### rustc

```console
$ tar xzf rustc-<version>-i686-unknown-netbsd.tar.xz
$ cd rustc-<version>-i686-unknown-netbsd/
$ doas bash install.sh --prefix=/opt/rust
```

### rust-std

```console
$ tar xzf rust-std-<version>-i686-unknown-netbsd.tar.xz
$ cd rust-std-<version>-i686-unknown-netbsd/
$ doas bash install.sh --prefix=/opt/rust
```

### cargo

```console
$ tar xzf cargo-<version>-i686-unknown-netbsd.tar.xz
$ cd cargo-<version>-i686-unknown-netbsd/
$ doas bash install.sh --prefix=/opt/rust
```
