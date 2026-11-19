# AnuraOS &nbsp; [![bluebuild build badge](https://github.com/hikiru/anura-os/actions/workflows/build.yml/badge.svg)](https://github.com/hikiru/anura-os/actions/workflows/build.yml)

This is my personal BlueBuild image based on secureblue, not intended for general use.

## ISO

If build on Fedora Atomic, you can generate an offline ISO with the instructions available [here](https://blue-build.org/how-to/generate-iso/#_top). These ISOs cannot unfortunately be distributed on GitHub for free due to large sizes, so for public projects something else has to be used for hosting.

## Verification

These images are signed with [Sigstore](https://www.sigstore.dev/)'s [cosign](https://github.com/sigstore/cosign). You can verify the signature by downloading the `cosign.pub` file from this repo and running the following command:

```bash
cosign verify --key cosign.pub ghcr.io/hikiru/anura-os
```
