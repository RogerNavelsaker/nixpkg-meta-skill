# nixpkg-meta-skill

Thin Nix packaging repo for [`Dicklesworthstone/meta_skill`](https://github.com/Dicklesworthstone/meta_skill).

## Upstream

- Repo: `Dicklesworthstone/meta_skill`
- Upstream crate version: `0.1.1`
- Pinned commit: `114c1e250b2c75b99b3d34daadcb7b2c01bb07e5`

## Usage

```bash
nix build
nix run
```

The package fetches the pinned upstream source directly from GitHub, stages only the crate inputs needed for packaging, and installs the `ms` binary.
