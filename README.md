# Termcraft APT repository

The signed Debian/Ubuntu amd64 feed is live at [pagel-s.github.io/termcraft-apt/apt/](https://pagel-s.github.io/termcraft-apt/apt/). Follow the [APT setup guide](https://pagel-s.github.io/termcraft/distribution/#apt-setup-after-publication) to verify the signing key and install Termcraft.

The `beta` suite includes prereleases and retains three supported versions. Public keys and fingerprint are in this repository; the signing key is held only in the `APT_SIGNING_PRIVATE_KEY` Actions secret. Back up the private key securely and replace the public key, fingerprint and secret together before expiry.

Package updates follow verified, published [Termcraft releases](https://github.com/pagel-s/termcraft/releases). The Update workflow checks hourly and can be run manually.

[Installation and release guide](https://github.com/pagel-s/termcraft/blob/main/docs/distribution.md). Shared tooling is pinned to a reviewed source commit; update both workflow references together when changing it.
