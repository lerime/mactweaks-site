# mactweaks.lerimedt.com

Website and Sparkle update feed for MacTweaks, served by GitHub Pages.

- `appcast.xml`: the signed update feed, written by `publish.sh` in the MacTweaks repo
- `updates/`: one zip per version, with its release notes, for Sparkle
- `downloads/`: the disk images; `MacTweaks.dmg` is always the latest

Do not edit `appcast.xml` by hand: its signatures come from the EdDSA key in the release keychain.
