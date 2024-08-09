# Karaberus Flatpak

## Add repository

```
flatpak --user --no-gpg-verify remote-add karaberus https://japan7.github.io/karaberus-flatpak/repo/
flatpak --user update --appstream karaberus
```

## Install karaberus

```
flatpak --user install karaberus moe.japan7.karaberus
```
