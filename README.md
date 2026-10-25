# Termcraft APT repository

Package updates follow verified, published [Termcraft releases](https://github.com/pagel-s/termcraft/releases). The beta has not been published yet; this repository is ready and the updater remains idle until supported release metadata is available.

[Installation and release guide](https://github.com/pagel-s/termcraft/blob/beta/terminal-reborn/docs/distribution.md). The Update workflow checks hourly and can be run manually. Its shared tooling is pinned to a reviewed source commit; update both workflow references together when changing it.

After publication the signed feed is hosted at https://pagel-s.github.io/termcraft-apt/apt . The `beta` suite includes prereleases and retains three supported versions. Public keys and fingerprint are in this repository; the signing key is held only in the APT_SIGNING_PRIVATE_KEY Actions secret. Back up the private key securely and replace the public key, fingerprint and secret together before expiry.
