# All

```sh
nix shell nixpkgs#cmake
```

# C Bindings

```sh
MACOSX_DEPLOYMENT_TARGET=15.0 cargo b -j8 --release
```

# libsql-ffi (sqlite3mc_shell)

```sh
cargo b --features multiple-ciphers -j8 --release
```
