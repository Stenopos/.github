<p align="center"><img src="assets/full-banner.png" alt="Stenopos" width="600"></p>

# Stenopos

A memory-safe, capability-based operating system and the language it is written in.

*Ἀσφάλεια περὶ πλείστου: security above all.*

- Documentation: https://stenopos.github.io
- Toolchain releases: [Syntagma](https://github.com/Stenopos/Syntagma)

## The names

Every part of Stenopos carries a Greek name. Here is what each one is, how to
say it, and where it stands.

<!-- brand:names -->
**Platform**

| Name | Greek | Say it | Meaning | What it is | Status | Version |
|------|-------|--------|---------|------------|--------|---------|
| **Stenopos** | Στενωπός | STEN-oh-pos | The narrow pass | The platform as a whole: the OS, the language, its toolchain and the apps | In progress | — |
| **Stenopos OS** | Στενωπός | STEN-oh-pos | The narrow pass | The operating system, built to be the hardest place for an attack to get through | Designed | TBD |
| [**Stenopos language**](https://github.com/Stenopos/Syntagma) | Στενωπός | STEN-oh-pos | The narrow pass | The programming language the platform is written in (`.sten`); released through Syntagma | In progress | [![Syntagma version](https://img.shields.io/github/v/release/Stenopos/Syntagma?include_prereleases&sort=semver&display_name=tag&label=&color=7a5a1c&style=flat-square)](https://github.com/Stenopos/Syntagma/releases) |
| [**Syntagma**](https://github.com/Stenopos/Syntagma) | Σύνταγμα | SIN-tag-ma | A formation; an ordered body of troops | The toolchain that compiles and builds Stenopos code: compiler, standard library, `tagma` and the language server | In progress | [![Syntagma version](https://img.shields.io/github/v/release/Stenopos/Syntagma?include_prereleases&sort=semver&display_name=tag&label=&color=7a5a1c&style=flat-square)](https://github.com/Stenopos/Syntagma/releases) |
| [**Tagma**](https://github.com/Stenopos/Syntagma) | Τάγμα | TAG-ma | A disciplined unit drawn up in formation | The build tool and dependency manager (`tagma`); ships with Syntagma, same version | In progress | [![Syntagma version](https://img.shields.io/github/v/release/Stenopos/Syntagma?include_prereleases&sort=semver&display_name=tag&label=&color=7a5a1c&style=flat-square)](https://github.com/Stenopos/Syntagma/releases) |

**The OS**

| Name | Greek | Say it | Meaning | What it is | Status | Version |
|------|-------|--------|---------|------------|--------|---------|
| **Agoge** | Ἀγωγή | ah-go-GAY | The Spartan training system that formed every citizen | The kernel, in compartments (layers L0 to L4) | Designed | TBD |
| **Ephor** | Ἔφορος | EF-or | The overseers who supervised Spartan life, kings included | The init and service manager | Designed | TBD |
| **Panoplia** | Πανοπλία | pan-oh-PLEE-ah | A hoplite's complete armour, the root of "panoply" | The OS package manager (`pano`, `.pano` packages) | Designed | TBD |
| **Stoa** | Στοά | STOH-ah | A covered colonnade where goods were kept | The filesystem | Designed | TBD |
| **Skytale** | Σκυτάλη | SKIT-ah-lee | Sparta's cipher: a staff a message strip was wound around | The verified cryptography library | Designed | TBD |
| **Phalanx** | Φάλαγξ | FAY-lanks | The wall of shields, each protecting the soldier beside it | The security center, firewall and malware scanner | Designed | TBD |
| **Phoenix** | Φοῖνιξ | FEE-nix | The bird that rises again from its ashes | Recovery mode | Designed | TBD |

**Apps**

| Name | Greek | Say it | Meaning | What it is | Status | Version |
|------|-------|--------|---------|------------|--------|---------|
| **Hoplite** | Ὁπλίτης | HOP-lite | The Spartan citizen-soldier | The command shell (`hop`) | Designed | TBD |
| **Kopis** | Κοπίς | KOH-pis | A short, heavy Spartan blade | The terminal | Designed | TBD |
| **Laconic** | Λακωνικός | lah-KON-ik | "Of Laconia": Spartans were famous for short, pointed speech | The text and code editor | Not started | TBD |
| **Periplus** | Περίπλους | PERR-ih-plus | A voyage around the coasts, and the logbook of it | The web browser and its memory-safe engine | Designed | TBD |
| **Keryx** | Κῆρυξ | KAIR-ix | The herald who carried messages between cities | Mail and messaging | Not started | TBD |
| **Hemera** | Ἡμέρα | HEM-er-ah | The goddess of the day | The calendar | Not started | TBD |
| **Agora** | Ἀγορά | AG-or-ah | The public marketplace and gathering place | The app store | Not started | TBD |
| **Lyra** | Λύρα | LIE-rah | The lyre, the Greek string instrument | The media player and media framework | Designed | TBD |

**Devices**

| Name | Greek | Say it | Meaning | What it is | Status | Version |
|------|-------|--------|---------|------------|--------|---------|
| **Stenopos Trireme** | Τριήρης | TRY-reem | The fast Greek warship with three banks of oars | The mobile profile | Designed | TBD |
| **Stenopos Lochos** | Λόχος | LOH-khos | The smallest Spartan unit | The embedded and industrial profile | Designed | TBD |
<!-- /brand:names -->
