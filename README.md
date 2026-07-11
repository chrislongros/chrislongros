# Hi there, I'm Christos

![Profile Views](https://komarev.com/ghpvc/?username=chrislongros&color=blue&style=flat)

> UNIX enthusiast · Open-source developer · AUR package maintainer · R package author · FreeBSD porter

---

## About me

I am a medical doctor and an open-source developer focused on **FreeBSD/OpenZFS ecosystem**, **Arch Linux** packaging and **self-hosted infrastructure**. I also build tools around **spaced repetition** (Anki/FSRS).

- Main interests: filesystems, storage internals, self-hosted infrastructure, spaced repetition learning, EDC systems
- Languages: mainly C, R
- Blog: [chrislongros.com](https://chrislongros.com/)
- Mastodon: [@chrislongros@mastodon.social](https://mastodon.social/@chrislongros)
- ORCID: [0009-0001-2717-0857](https://orcid.org/0009-0001-2717-0857)

---

## Why OpenZFS

The data integrity that OpenZFS provides is crucial for me — it secures invaluable data such as family photos.

Main features:

- **End-to-end checksumming** — a checksum is computed and stored for every allocated block
- **Self-healing** — on a checksum mismatch, the block is restored from a mirror copy or RAID-Z parity and the corrected data is rewritten to disk
- **Pool scrubbing** — a pool-wide verification that validates every allocated block: user data, metadata, and parity

---

## What I work on

- **[OpenZFS](https://github.com/openzfs/zfs)** — unit tests, CI, test suite, documentation
- **[FreeBSD](https://github.com/freebsd/freebsd-src)** — src commits (device drivers such as rge and ure, EFI loader, man pages), ports, documentation
- **R** — [ankiR](https://cran.r-project.org/package=ankiR) on CRAN, [digest](https://github.com/eddelbuettel/digest) contributor, [freebsdcontribs](https://cran.r-project.org/package=freebsdcontribs) on CRAN, more on [r-universe](https://chrislongros.r-universe.dev)
- **Arch Linux** — 120+ AUR packages, [BioArchLinux](https://github.com/BioArchLinux/Packages), [archinstall](https://github.com/archlinux/archinstall)
- **Greek localization** — [TrueNAS WebUI](https://github.com/truenas/webui), FreeBSD Handbook, Anki
- **[Anki](https://github.com/ankitects/anki)** — self-hosted sync server, tooling, upstream fixes, localization
- **Homelab** — TrueNAS Scale, ZFS, Tailscale, 80+ containers

---

## Popular repositories

- **[anki-sync-server-enhanced](https://github.com/chrislongros/anki-sync-server-enhanced)** — self-hosted Anki sync server with multi-user support, auto-updates, healthchecks, and Docker secrets
- **[anki-snapshot](https://github.com/chrislongros/anki-snapshot)** — git-based version control for Anki collections with human-readable diffs
- **[anki-desktop-docker](https://github.com/chrislongros/anki-desktop-docker)** — browser-accessible Anki Desktop via KasmVNC, always on the latest version
- **[ankiR](https://github.com/chrislongros/ankiR)** — R package for reading Anki databases with FSRS parameter support
- **[truenas-tailscale-cert-automation](https://github.com/chrislongros/truenas-tailscale-cert-automation)** — automated Tailscale TLS certificate management for TrueNAS

---

## My GitHub Stats

<p align="center">
  <img src="./profile/stats.svg" alt="Christos Longros' GitHub Stats" />
</p>
