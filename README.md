# cloudflared-riscv64

Build-only repository for community Linux `riscv64` releases of the exact
official [`cloudflare/cloudflared`](https://github.com/cloudflare/cloudflared)
release tags.

Each release contains:

- `cloudflared-linux-riscv64`, a statically linked binary
- `SHA256SUMS`
- `BUILD-INFO.md` with the upstream source commit and build details
- GitHub build provenance attestation

Builds are started manually from **Actions → Build cloudflared riscv64** by
providing an official release tag. A daily check dispatches a build for a new
stable upstream release when that version is not already published. Existing
releases are never overwritten.

These are community builds and are not official Cloudflare release assets.
