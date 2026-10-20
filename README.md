# Rustup

Mirror of official [rustup](https://rust-lang.github.io/rustup/installation/other.html#manual-installation) binaries, repackaged so they can be installed with [`ghr`](https://cataggar.github.io/ghr/):

```sh
ghr install cataggar/rustup-init
rustup-init -y
```

Binaries are downloaded from
`https://static.rust-lang.org/rustup/archive/{rustup-version}/{target-tuple}/rustup-init[.exe]`
and verified against the upstream `.sha256` files before repackaging, as described
in the [rustup installation documentation](https://rust-lang.github.io/rustup/installation/other.html).
Only the archives are published; GitHub provides their SHA-256 digests.
