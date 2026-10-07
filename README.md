# Custom Mason Registry

Based on [mason-registry](https://github.com/mason-org/mason-registry), with
only the packages I need to customize.

> [!important]
> Remember to execute `:MasonInstall yq` on a fresh installation.

## Supported packages

### [`asm-lsp`](https://github.com/bergercookie/asm-lsp)

The existing schema of `asm-lsp` available on `mason-registry` relies on `cargo`
for the installation.
Their approach makes sense, since `cargo` supports multiple architecture by
default, but I don't want to install it on my machine, luckily, `asm-lsp` offers
a prebuilt binary for `linux-x86_64`.
