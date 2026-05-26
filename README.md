# debian-trixie-i386

Unified Debian Trixie i386 port. Combines the linux kernel and CD image builds
needed to bring 32-bit x86 (i386) support to Debian Trixie.

## Structure

| Directory | Source | Purpose |
|-----------|--------|---------|
| `linux/`  | [debian-linux-i386-trixie](https://github.com/Interested-Deving-1896/debian-linux-i386-trixie) | Linux kernel package with i386 config |
| `cd/`     | [debian-cd-i386-trixie](https://github.com/Interested-Deving-1896/debian-cd-i386-trixie)       | CD image build tooling |

## Branches

- `main` — unified monorepo (this branch)
- Source repos track `debian/6.12/trixie-i386` and `buildd/trixie` respectively

## Upstream

- Kernel: [salsa.debian.org/kernel-team/linux](https://salsa.debian.org/kernel-team/linux) — `debian/6.12/trixie`
- CD: [salsa.debian.org/images-team/debian-cd](https://salsa.debian.org/images-team/debian-cd) — `buildd/trixie`

Original i386 work by [piernov](https://github.com/piernov):
- [piernov/debian-linux-i386](https://github.com/piernov/debian-linux-i386)
- [piernov/debian-cd-i386](https://github.com/piernov/debian-cd-i386)
