# go

Go 1.27.3: the compiler, linker, go command and the standard library

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install go
```

| | |
|---|---|
| Version | 1.27.3 |
| Licence | BSD-3-Clause |
| Upstream | https://go.dev |
| Needs | [`busybox`](https://github.com/Artfical/tpkg-busybox), [`ca-certificates`](https://github.com/Artfical/tpkg-ca-certificates) |
| Needs tOS build | 620 or newer |
| Size | 101031865 bytes (371060041 unpacked) |
| SHA-256 of the `.tpkg` | `515c435cbae33c44d9370e00c7467ea633b13f69dc5ce3d6a2490b9b9d3c2256` |

## Commands it adds

| Command | Runs |
|---|---|
| `go` | `bin/go-tos` |
| `gofmt` | `bin/gofmt` |

## Download

The package file (`go-1.27.3.tpkg`) and the sources it was built from are the assets of the
[v1.27.3 release](https://github.com/Artfical/tpkg-go/releases/tag/v1.27.3).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- (none: see the upstream page above)

Check a download: `sha256sum go-1.27.3.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: BSD-3-Clause. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
