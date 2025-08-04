# OpenCloud Desktop

Flatpak manifest for the [OpenCloud Desktop Client](https://github.com/opencloud-eu/desktop).

## Build and install

```bash
mkdir repo builddir
flatpak run org.flatpak.Builder --user --install-deps-from=flathub --repo=repo --install builddir eu.opencloud.desktop.yml
```

## Similar repos

The flatpak variants of the [nextcloud](https://github.com/flathub/com.nextcloud.desktopclient.nextcloud) and [owncloud](https://github.com/flathub/com.nextcloud.desktopclient.nextcloud) desktop client are built in a very similar way.
Hence, any kind of packaging/flatpak-specific issue might be common among these repos and might be solved collaboratively.
