This repo contains a working version of the spotify x86-64 linux client packaged as an flatpak.

There is a pre-build version available, which you can install with:
```
flatpak install --from https://s3.amazonaws.com/alexlarsson/spotify-repo/spotify.flatpakref
```

Note: If you build this yourself you need the gnome remote configured, for example:
```
flatpak remote-add --if-not-exists gnome https://sdk.gnome.org/gnome.flatpakrepo
```
