# イーライ Voicebank Line — Voicebank Specification

This is the canonical technical overview of the イーライ voicebank family. The project is developed as a continuous voicebank line whose recordings, expression and presentation can grow from one generation to the next.

## Generation structure

### Generation 1 — イーライ

The original Japanese UTAU voicebank and the starting point of the project. Its vocal and visual presentation has a more masculine origin than the later generations.

- [Character profile](../iirai.html)
- [GitHub release](https://github.com/ilyaminineli/Iirai/releases/tag/%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [BowlRoll distribution](https://bowlroll.net/file/349204)

### Generation 2 — 茜音イーライ

The second generation expanded the recording and developed a softer, more feminine and less convention-bound vocal/character expression while retaining the core voice.

The released bank has three pitches: A3 / F3 / C3. It provides improved phoneme clarity, a clearer and more confident upper range, and a warm, bass-leaning core.

- [Character profile](../akane-iirai.html)
- [GitHub release](https://github.com/ilyaminineli/Iirai/releases/tag/%E8%8C%9C%E9%9F%B3%E3%82%A4%E3%83%BC%E3%83%A9%E3%82%A4)
- [BowlRoll distribution](https://bowlroll.net/file/350273)

### Generation 3 — 茜音イーライ・暁

The incoming third generation continues the same line with cleaned samples, new appends and extras, and a new visual design. The final technical specification will be expanded as the new recordings are completed.

- [Character profile](../akane-iirai-akatsuki.html)

## Character / Credits

- Presentation: Fluid / androgynous
- Pronouns: he/him
- Creator: Ilya Minin (Eli)
- Voice Provider: Ilya Minin (Eli)
- Illustrator: Schenchik
- OTO / Technical: eikton

The real voice provider, Ilya Minin (Eli), identifies as non-binary and is exploring a place between genders. The evolution of the character and voicebank follows that movement away from a masculine origin toward a more androgynous, fluid and personally comfortable expression.

## Current released technical specification — 茜音イーライ

- Engine: UTAU / OpenUtau
- Language: Japanese
- Recording method: CVVC
- Encoding: Romaji-encoded, CVVC aliased
- Pitches: A3 / F3 / C3
- Range: G#3–D3
- Optimum BPM: 70–120
- Genres: Dark pop, industrial, experimental
- Features: Consonant clarity, high end and bass
- Primary recommendation: TIPS, especially for bass preservation
- Other recommendations: Moresampler, WORLDLINE-R, wavtool4vcv

## Moresampler expressions

- Velocity (0–200): Consonant strength
- Gender (-100 to 100): Formant shift (deep/light)
- Tone Shift (-36 to 36): Pitch selection
- Breathiness (0–100): Added noise
- Tension (-200 to 200): Voice strength
- Growl (0–100): Guttural effect

## Voicebank characteristics

The family is built around a warm, textured core with increasing access to upper-register and expressive material as the generations develop. Later generations are particularly suited to expressive phrasing, fast or rambling lines, chant-like parts and subtle glitched ad-libs.

The goal is not to freeze one “correct” form of the voice. The voicebank documents a living artistic process in which vocal timbre, presentation and character expression can change over time.

## Canonical source

For released technical values, the current official manual and release documentation are authoritative. Historical information about Generation 1 remains valuable for documenting the project's origin and should be kept alongside current generation metadata.
