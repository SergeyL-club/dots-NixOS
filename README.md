# dots-NixOS

Установка диска через конфиг disko:

sudo nix --experimental-features "nix-command flakes" run github:nix-community/disko -- --mode disko ./disko.nix

Затем установка:

nixos-generate-config --root /mnt && nixos-install
