# dotfiles

## Setup

- Install `nix`
```
curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | sh -s -- install
```

- Install `home-manager`
```
nix run home-manager -- init --switch .
```

- Run depending on your system
```
# Linux
home-manager switch --flake .#arian-linux
```

```
# MacOS
home-manager switch --flake .#arian-macos
```
