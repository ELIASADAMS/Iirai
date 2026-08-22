# 茜音イーライ (Akane Iirai) — Japanese CVVC UTAU Voicebank

Official repository for **茜音イーライ (Akane Iirai)**, the updated version of the original **イーライ (Iirai)** voicebank by **Ilya Minin (Eli)**.

> A scruffy, bright-eyed tinkerer with a warm bass voice, a clearer upper range, and a habit of cutting reality into jump-cuts.

## Quick Links

- [Official Website](https://eliasadams.github.io/Iirai/)
- [Download](https://github.com/ELIASADAMS/Iirai/releases)
- [UTAU Wiki — original Iirai reference](https://utau.fandom.com/wiki/%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [Documentation](docs/README.md)
- [Official Manual](docs/MANUAL.md)
- [Technical Specification](docs/VOICEBANK.md)
- [Usage Guide](docs/USAGE.md)
- [Character](docs/CHARACTER.md)
- [Version History](docs/VERSIONS.md)
- [Media Archive](docs/MEDIA.md)
- [Future Revisions](docs/RELEASES.md)
- [Terms of Use](TERMS.md)
- [Machine-readable Metadata](metadata/voicebank.json)
- [Changelog](changelog.html)

## Voicebank Specifications

| Property | Current official value |
|---|---|
| Name | 茜音イーライ (Akane Iirai) |
| Previous version | イーライ (Iirai) |
| Engine | UTAU / OpenUtau |
| Language | Japanese |
| Recording method | CVVC |
| Encoding | Romaji-encoded, CVVC aliased |
| Pitches | A3 / F3 / C3 |
| Range | G#3–D3 |
| Optimum BPM | 70–120 |
| Genres | Dark pop / Industrial / Experimental |
| Features | Consonant clarity / High end / Bass |
| Recommended | TIPS / Moresampler / WORLDLINE-R / wavtool4vcv |

## About

茜音イーライ is the updated iteration of the original イーライ. The current manual describes improved phoneme clarity compared with the first iteration, while retaining a warm, bass-leaning core and extending it into a clearer, more confident upper range.

The updated bank is designed for expressive phrasing, fast or rambling lines, chant-like parts and subtle glitched ad-libs.

## Installation

1. Download the latest release from [GitHub Releases](https://github.com/ELIASADAMS/Iirai/releases).
2. Extract the voicebank archive.
3. Install it into your UTAU `voice` directory or import it into OpenUtau according to your normal workflow.

## Usage

Start with **TIPS**, especially when you want to preserve the bank's bass character. Moresampler is recommended for custom expression controls; WORLDLINE-R and wavtool4vcv are also supported recommendations.

See [docs/USAGE.md](docs/USAGE.md) for practical setup and future examples.

## Character

Akane Iirai is fluid/non-binary and uses he/him pronouns. He is a scruffy tinkerer known as 怪人ハサミ (Kaijin Hasami, “Scissor Kaijin”), with messy orange hair, freckles, greenish eyes, goggles, gear motifs, tool belts and oversized scissors.

See [docs/CHARACTER.md](docs/CHARACTER.md) for the current character archive and [docs/VERSIONS.md](docs/VERSIONS.md) for the relationship to the original Iirai.

## Terms of Use

Current terms are maintained in [TERMS.md](TERMS.md). Use that document as the canonical version.

## Credits

- **Creator:** Ilya Minin (Eli)
- **Voice Provider:** Ilya Minin (Eli)
- **Illustrator:** Schenchik
- **OTO / Technical:** eikton

## Repository Structure

- `docs/` — canonical documentation and project history
- `metadata/` — machine-readable voicebank metadata
- `assets/` — prepared location for future organized assets
- `TERMS.md` — canonical terms
- `index.html`, `info.html`, `download.html`, `changelog.html`, `contact.html` — GitHub Pages site
- `sample.wav`, `solfege.wav` — current audio samples

Existing root-level artwork is intentionally preserved for now so the current GitHub Pages site stays stable. It can be migrated into `assets/` together with all HTML path updates in a dedicated pass.

## Historical Reference

The original **イーライ (Iirai)** remains part of the archive. The UTAU Wiki page is preserved as a historical/reference source rather than the current technical specification for Akane Iirai. citeturn198529search0

## Contact

- **Ilya Minin (Eli):** https://t.me/ilyaminineli
- **Schenchik:** https://t.me/shenchik
- **eikton:** https://t.me/e1kton

## Source of Truth

The supplied official Akane Iirai manual is authoritative for the current release's metadata, credits and terms. Older Iirai information may be retained for historical context, but must not overwrite current Akane Iirai metadata.
