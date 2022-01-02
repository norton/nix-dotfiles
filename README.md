# Dotfiles

A repository of configuration files (with the intention) to configure your
(macOS) home directory and those dotfiles declaratively.

# Prerequisites

Install
- [babashka](https://github.com/babashka/babashka).
- [jet](https://github.com/borkdude/jet).

# Quickstart

For quick installation use:

``` shell
$ bb nix:install
```

Restart your shell and then install Nix Flakes:

``` shell
$ bb nix:install-flakes
```

Then you're ready to go:

``` shellsession
$ bb nix:info
 - system: `"x86_64-darwin"`
 - host os: `Darwin 21.2.0, macOS 10.16`
 - multi-user?: `yes`
 - sandbox: `no`
 - version: `nix-env (Nix) 2.6.0pre20211217_6e6e998`
 - channels(root): `"nixpkgs-22.05pre342664.6f05cfdb1e7"`
 - nixpkgs: `/nix/var/nix/profiles/per-user/root/channels/nixpkgs`
```

Print the list of available tasks:

``` shell
$ bb tasks
```

# Links

- https://babashka.org

- https://nixos.org/manual/nix/stable/introduction.html
- https://nixos.wiki/wiki/Flakes

- https://www.softinio.com/post/moving-from-homebrew-to-nix-package-manager/

# License

Copyright © 2021-2022 Joseph Wayne Norton.

Distributed under the MIT License. See [LICENSE](./LICENSE).
