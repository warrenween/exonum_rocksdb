exonum_rocksdb
============
[![Build Status](https://travis-ci.org/exonum/exonum_rocksdb.svg?branch=master)](https://travis-ci.org/exonum/exonum_rocksdb)
[![crates.io](http://meritbadge.herokuapp.com/rocksdb)](https://crates.io/crates/exonum_rocksdb)

[documentation](https://docs.rs/rocksdb/0.6.0/rocksdb/)

Feedback and pull requests welcome!  If a particular feature of RocksDB is important to you, please let me know by opening an issue, and I'll prioritize it.

```rust
[dependencies]
rocksdb = "0.6.0"
```

This binding is statically linked with a specific version of RocksDB. If you want to build it yourself, make sure you've also cloned the RocksDB and Snappy submodules:

    git submodule update --init --recursive
