# Tandem releases

Signed builds of **Tandem** for Windows. The app updates itself from here: it reads `latest.json`,
checks the Ed25519 signature against the release key built into Tandem, checks the download's
SHA-256, and only then installs. Unsigned or altered files are refused.

You don't need to download anything here by hand except the very first time:
grab `Tandem.exe` from the latest release, put it in its own folder, and run it.

## Source code (GPL)

Tandem's Studio is built on OBS Studio's engine (libobs), which is licensed under the GNU GPL v2.
Tandem is therefore distributed under the GPL v2 as well. If you received Tandem, you're entitled
to its complete corresponding source code: ask Nick (the maintainer) and it will be provided at no
charge beyond the cost of delivery. This offer is valid for three years from each release.
