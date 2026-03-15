# Hi there, I'm Christos

![Profile Views](https://komarev.com/ghpvc/?username=chrislongros&color=blue&style=flat)

> UNIX enthusiast · Open-source developer · AUR packager · Spaced repetition nerd

---

## About me

I am an open-source developer with a strong focus on the **FreeBSD/OpenZFS ecosystem**, **Arch Linux** packaging, and **self-hosted infrastructure**. I maintain several AUR packages, have published an R package on CRAN, and actively contribute to upstream projects in the UNIX and spaced repetition space. Alongside my development work, I build **EDC database systems** for clinical research — self-hosted alternatives to commercial platforms like REDCap.

- Ask me about **ZFS, FreeBSD, Anki, FSRS, Arch Linux, TrueNAS, Docker**
- Currently learning: **C/C++, Rust, R**
- Main interests: filesystems, storage internals, self-hosted infrastructure, spaced repetition science, EDC systems
- Blog: [chrislongros.com](https://chrislongros.com/)
- Mastodon: [@chrislongros@mastodon.social](https://mastodon.social/@chrislongros)

---

## Highlights

- **AUR maintainer** — 8 packages covering spaced repetition tooling and medical imaging, plus co-maintainer of `r-rlang`
- **CRAN author** — [ankiR](https://cran.r-project.org/package=ankiR), a comprehensive R toolkit for Anki flashcard database analysis (137 functions)
- **FreeBSD contributor** — kernel driver patches via [Phabricator](https://reviews.freebsd.org), new ports for [py-fsrs](https://github.com/freebsd/freebsd-ports/pull/473) and [py-genanki](https://github.com/freebsd/freebsd-ports/pull/474), handbook updates, and Greek translations
- **OpenZFS contributor** — [5 merged PRs](https://github.com/openzfs/zfs/pulls?q=is%3Apr+author%3Achrislongros+is%3Amerged) including error message improvements, man pages, and undocumented flag cleanup
- **EDC systems developer** — self-hosted clinical data capture platforms as REDCap alternatives
- **Homelab operator** — 80+ containers on TrueNAS Scale with ZFS, Tailscale, Prometheus, and S3-compatible object storage

---

## Projects

### Anki & Spaced Repetition

| Project | Description |
|---|---|
| [**ankiR**](https://github.com/chrislongros/ankiR) | R package on CRAN — read & analyse Anki SQLite databases, retention stats, FSRS parameters (137 functions) |
| [**rfsrs**](https://github.com/open-spaced-repetition/r-fsrs) | Rust/R bindings for the FSRS-6 spaced repetition algorithm (under open-spaced-repetition org) |
| [**anki-snapshot**](https://github.com/chrislongros/anki-snapshot) | Git-based version control for Anki collections with human-readable diffs |
| [**anki-sync-server-enhanced**](https://github.com/chrislongros/anki-sync-server-enhanced) | Self-hosted Anki sync server — multi-user, auto-updates, web dashboard, TLS, Prometheus metrics |
| [**anki-desktop-docker**](https://github.com/chrislongros/anki-desktop-docker) | Browser-accessible Anki Desktop with KasmVNC — always latest version |
| [**Anki-Cloze-Deletion**](https://github.com/chrislongros/Anki-Cloze-Deletion) | Modern dark-themed Anki cloze note type for medical students |

### TrueNAS & Homelab

| Project | Description |
|---|---|
| [**truenas-scripts**](https://github.com/chrislongros/truenas-scripts) | TrueNAS automation — Tailscale Serve preservation, certificate renewal with cleanup, app updates |
| [**truenas-tailscale-cert-automation**](https://github.com/chrislongros/truenas-tailscale-cert-automation) | Automated Tailscale SSL certificate import for TrueNAS UI |

### R Data Packages

| Project | Description |
|---|---|
| [**osscontribs**](https://github.com/chrislongros/osscontribs) | Open source project contributor growth statistics (R data package) |
| [**freebsdcontribs**](https://github.com/chrislongros/freebsdcontribs) | FreeBSD Phabricator contributor growth statistics (R data package) |

### AUR Packages

| Package | Description |
|---|---|
| [`anki-snapshot`](https://aur.archlinux.org/packages/anki-snapshot) | Git-based version control for Anki collections |
| [`r-ankir`](https://aur.archlinux.org/packages/r-ankir) | Comprehensive R toolkit for Anki flashcard analysis (137 functions) |
| [`r-fsrs`](https://aur.archlinux.org/packages/r-fsrs) | R bindings for the FSRS-6 spaced repetition algorithm |
| [`nifticlib`](https://aur.archlinux.org/packages/nifticlib) | NIfTI-1 neuroimage format I/O library |
| [`xmedcon`](https://aur.archlinux.org/packages/xmedcon) | Open-source medical image conversion toolkit |
| [`python-fsrs`](https://aur.archlinux.org/packages/python-fsrs) | Free Spaced Repetition Scheduler — Python implementation |
| [`python-ankipandas`](https://aur.archlinux.org/packages/python-ankipandas) | Analyse and manipulate Anki flashcards using pandas |
| [`python-genanki`](https://aur.archlinux.org/packages/python-genanki) | Python 3 library for generating Anki decks |

*Co-maintaining:* [`r-rlang`](https://aur.archlinux.org/packages/r-rlang) — Functions for Base Types and Core R / Tidyverse Features

---

## Upstream Contributions

| Project | Status |
|---|---|
| [**OpenZFS**](https://github.com/openzfs/zfs) | [5 merged](https://github.com/openzfs/zfs/pulls?q=is%3Apr+author%3Achrislongros+is%3Amerged) (zpool error messages, man pages, flag cleanup), [3 open](https://github.com/openzfs/zfs/pulls?q=is%3Apr+author%3Achrislongros+is%3Aopen) (zarcsummary man page, zilstat AUTHORS, device failure reporting) |
| [**FreeBSD/freebsd-src**](https://github.com/freebsd/freebsd-src) | Kernel driver patches via [Phabricator](https://reviews.freebsd.org) — rge(4) silicon revision logging ([D55402](https://reviews.freebsd.org/D55402), committed), C-style comments ([D55743](https://reviews.freebsd.org/D55743)) |
| [**FreeBSD/freebsd-ports**](https://github.com/freebsd/freebsd-ports) | 2 new ports under review — [py-fsrs](https://github.com/freebsd/freebsd-ports/pull/473), [py-genanki](https://github.com/freebsd/freebsd-ports/pull/474) |
| [**FreeBSD/freebsd-doc**](https://github.com/freebsd/freebsd-doc) | [6 open PRs](https://github.com/freebsd/freebsd-doc/pulls?q=is%3Apr+author%3Achrislongros+is%3Aopen) — handbook cleanup, Greek translations |
| [**TrueNAS WebUI**](https://github.com/truenas/webui) | [7 merged](https://github.com/truenas/webui/pulls?q=is%3Apr+author%3Achrislongros+is%3Amerged) — bug fixes, replication wizard fix, Greek translations |
| [**TrueNAS Apps**](https://github.com/truenas/apps) | [Anki Sync Server Enhanced](https://github.com/truenas/apps/pull/4282) added as community app |
| [**Immich**](https://github.com/immich-app/immich) | [2 merged](https://github.com/immich-app/immich/pulls?q=is%3Apr+author%3Achrislongros+is%3Amerged) — mobile nav bar fix, docs clarification |
| [**ankitects/anki**](https://github.com/ankitects/anki) | [1 open PR](https://github.com/ankitects/anki/pull/4548) — simulator graph fix |
| [**ankitects/anki-core-i18n**](https://github.com/ankitects/anki-core-i18n) | 181 commits — Greek (el) Fluent translations via Pontoon |
| [**ankitects/anki-manual**](https://github.com/ankitects/anki-manual) | 1 merged (FSRS docs), [1 open](https://github.com/ankitects/anki-manual/pull/421) (search keyword docs) |
| [**ankimcp/anki-mcp-server-addon**](https://github.com/ankimcp/anki-mcp-server-addon) | [FSRS parameter tools merged](https://github.com/ankimcp/anki-mcp-server-addon/pull/14) |
| [**open-spaced-repetition/fsrs4anki-helper**](https://github.com/open-spaced-repetition/fsrs4anki-helper) | [3 merged](https://github.com/open-spaced-repetition/fsrs4anki-helper/pulls?q=is%3Apr+author%3Achrislongros+is%3Amerged) — Greek translations |
| [**tidyverse/forcats**](https://github.com/tidyverse/forcats) | [1 open PR](https://github.com/tidyverse/forcats/pull/391) — `desc` argument for `fct_infreq()` |
| [**BioArchLinux/Packages**](https://github.com/BioArchLinux/Packages) | [r-ankir package merged](https://github.com/BioArchLinux/Packages/pull/305) |
| [**vim/vim**](https://github.com/vim/vim) | [Greek installer merged](https://github.com/vim/vim/pull/14148) |
| [**archlinux/archinstall**](https://github.com/archlinux/archinstall) | [Greek translations merged](https://github.com/archlinux/archinstall/pull/2284) |

---

## Homelab

Running a **TrueNAS Scale** homelab with:

- 80+ Docker containers managed via **Portainer**
- **ZFS** storage pools across HDDs and NVMe SSDs, with I/O-heavy workloads on dedicated SSD vdevs
- **Tailscale Serve** for secure, zero-config remote access with automated certificate renewal
- **Garage** and **RustFS** for S3-compatible object storage and automated backups
- Self-hosted Anki sync server, Prometheus/Grafana monitoring stack, and EDC research platforms

---

## Tech Stack

`R` · `Rust` · `C` · `C++` · `Python` · `Bash` · `Docker` · `ZFS` · `Arch Linux` · `TrueNAS` · `FreeBSD` · `Anki` · `FSRS`

---

## Stats

<a href="https://github.com/chrislongros">
  <img height=200 align="center" src="profile/stats.svg" />
</a>
<a href="https://github.com/chrislongros">
  <img height=200 align="center" src="profile/top-langs.svg" />
</a>
