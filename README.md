# Seed Store

Public, signed SeedApp packages for SeedOS.

- [Browse apps](https://ndr28s.github.io/seedos-store/)
- [Device catalog](https://ndr28s.github.io/seedos-store/catalog.json)
- [Signing public key](https://ndr28s.github.io/seedos-store/store-public.pem)

This repository contains distribution artifacts only. Firmware source, signing
private keys, deployment credentials and device data are not published here.
Installable packages contain the app's Lua code and declared assets.

The private publisher verifies packages before publishing. Existing ID/version
package paths are immutable; changes require a new version. Removing an app from
the catalog does not remove previously published package files.

SeedOS must be configured with this catalog URL and a separately verified signing
public key. Downloading the public key from this site alone is not a trust decision.
Live installation on hardware requires a working Wi-Fi connection.
