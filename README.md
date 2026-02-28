# Hey, I'm Christos

Thyroid surgeon by day, open-source tinkerer by night. I spend most of my free time building tools at the intersection of medicine, spaced repetition, and self-hosted infrastructure.

Right now I'm finishing my dissertation — analyzing around 500 thyroid surgery cases to predict postoperative hypocalcemia — and building the research database platforms to support that work (think self-hosted alternatives to REDCap).

When I'm not in the OR or writing R code, you'll probably find me contributing patches to FreeBSD, fiddling with ZFS internals, or packaging things for the AUR.

## What I've been building

**Spaced repetition tooling** is where most of my open-source energy goes. I'm a heavy Anki user and wanted better infrastructure around it:

- [anki-sync-server-enhanced](https://github.com/chrislongros/anki-sync-server-enhanced) — a self-hosted Anki sync server with multi-user support, auto-updates, and Prometheus metrics
- [anki-snapshot](https://github.com/chrislongros/anki-snapshot) — git-based version control for Anki collections with human-readable diffs
- [anki-desktop-docker](https://github.com/chrislongros/anki-desktop-docker) — browser-accessible Anki Desktop via KasmVNC
- [ankiR](https://github.com/chrislongros/ankiR) — an R package on CRAN for reading and analyzing Anki databases (137 functions, including FSRS parameter support)
- [rfsrs](https://github.com/chrislongros/rfsrs) — Rust/R bindings for the FSRS-6 spaced repetition algorithm

I also contribute to the broader [Open Spaced Repetition](https://github.com/open-spaced-repetition) ecosystem and maintain several related AUR packages (`python-fsrs`, `python-ankipandas`, `python-genanki`, `r-ankir`, `r-fsrs`, and more).

**On the systems side**, I maintain AUR packages for medical imaging tools ([xmedcon](https://aur.archlinux.org/packages/xmedcon), [nifticlib](https://aur.archlinux.org/packages/nifticlib)) and have open PRs against [FreeBSD kernel](https://github.com/freebsd/freebsd-src), [FreeBSD docs](https://github.com/freebsd/freebsd-doc), and [OpenZFS](https://github.com/openzfs/zfs). I've also contributed bug fixes to the TrueNAS WebUI and translations to Anki's i18n project.

## Homelab

My daily driver is Arch Linux, and my homelab runs TrueNAS Scale with 80+ Docker containers — everything from Immich and Jellyfin to a full Prometheus/Grafana monitoring stack. ZFS pools across HDDs and NVMe SSDs, Tailscale for remote access, and Garage/RustFS for S3-compatible backups. It's where I test most of what I build.

## Get in touch

- [chrislongros.com](https://chrislongros.com/)
- [@chrislongros@mastodon.social](https://mastodon.social/@chrislongros)

## Stats

<a href="https://github.com/chrislongros">
  <img height=200 align="center" src="profile/stats.svg" />
</a>
<a href="https://github.com/chrislongros">
  <img height=200 align="center" src="profile/top-langs.svg" />
</a>
