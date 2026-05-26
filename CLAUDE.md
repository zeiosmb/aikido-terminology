# CLAUDE.md

This project contains personal aikido study notes. The maintainer trains under the **USAF (United States Aikido Federation)** at Knoxville Aikikai under Crowell Sensei. Lineage runs Ueshiba → Akira Tohei → Crowell (Crowell Sensei was Tohei Sensei's *otomo*).

## Project Files

- `newvocab.md` — primary aikido terminology reference (concepts, etiquette, ranks, body, attacks, techniques, weapons, romanization, kanji-root index).
- [USAF Test Requirements.md](https://www.usaikifed.com/usaf-policies) — USAF Kyu/Dan exam requirements. **Formal document — preserve terminology verbatim. Do not rewrite.**

## Lineage & Terminology Preferences

### Prefer *jiyu waza* over *randori*

Akira Tohei Sensei (direct deshi of O-Sensei, senior to Yoshimitsu Yamada, led USAF technical direction until his death) considered **randori 乱取り** unsatisfying — likening it to a food buffet: "a little here, a little there." He preferred **jiyu waza 自由技** ("free techniques"), which emphasizes creative agency rather than scattered improvisation.

- In conversational use, lineage discussion, and study notes: **lead with *jiyu waza*.**
- In quotes from USAF exam documents: preserve *randori* as the formal term. The USAF's continued use of *randori* runs against Tohei's known wishes — institutional inertia, not endorsement. Flag the tension when relevant.

### Preserve Japanese terminology verbatim

Technique and concept names (Shomenuchi, Ikkyo, Kotegaeshi, Iriminage, etc.) stay in romaji. Do not anglicize, paraphrase, or substitute generic English. Translations belong in parenthetical gloss, not as replacements.

## Markdown Style Rules (universal)

These apply to every markdown file produced or edited in this project.

### Rule 1 — No `---` between H2 headings

Section headings alone are sufficient delimiters. Skip horizontal rules between consecutive `##` sections.

### Rule 2 — Blank line after every heading

Every `#`, `##`, `###`, etc. must be followed by a blank line before its content (paragraph, bullets, or anything else). Format:

```
## Section heading

First line of content.
```

NOT:

```
## Section heading
First line of content.
```

## Terminology Verification Standards

When proposing or editing Japanese terms, verify kanji and translations from multiple sources. Be alert to these specific errors that recur in source materials:

- **一教 Ikkyō** — the kanji is 教 (teaching), NOT 挙 (raise). Same for Nikyō, Sankyō, Yonkyō, Gokyō.
- **半身半立ち hanmi handachi** — the *tachi* is 立ち (standing), NOT 太刀 (long sword). Same homophone trap in **tachi waza** 立ち技.
- **回転投げ kaitennage** — 回転 = rotation. The "turn to heaven" gloss is folk etymology; there is no 天 in the word.
- **十字投げ jujinage** — 十字 = cross / cruciform (arms crossed in an X). Not "varied/winding."
- **極め kime** — "lock / fix" (not "poles").
- **立つ tatsu** — "to stand" uses 立つ, NOT 建つ (which means "to be built").
- **跪座 kiza** (alert kneeling, toes raised) is the standard form. Some texts use 危座.

For uncertain items:

- Mark with `(?)` inline.
- When uncertain, keep BOTH the user's original and the proposed correction.
- Note "confirm with sensei" rather than silently correcting.

## Romanization

**Hepburn romaji** (ヘボン式) is the standard throughout. Long vowels are marked with macrons (ō, ū) in formal contexts and often dropped in casual writing (aikido vs. aikidō, kyu vs. kyū). Both forms acceptable; aim for consistency within a document.

Other systems (Kunrei-shiki 訓令式, Nihon-shiki 日本式) appear in older or academic sources but should not be introduced when editing.

## Cultural Context Worth Knowing

- **Kotodama 言霊** ("word-spirit") — the belief that speaking a sound invites its meaning into reality. Foundational to O-Sensei's mystical teachings and to several lineage practices (misogi, kiai, chanting).
- **Shi / Ku avoidance** — *shi* (4) is a homophone of 死 (death); *ku* (9) of 苦 (suffering). Both are avoided in speech and formal numbering. In aikido drills, four-throw sequences are typically structured as **2 omote + 2 ura** rather than counted "1-2-3-4."

## Working Style

- Discuss before changing: when proposing edits to terminology or structure, surface the reasoning and let the user confirm before applying.
- Cite sources when verifying Japanese terms online.
- Use markdown links (`[name](path)`) for cross-references between project files. Avoid backticks/code formatting for file paths.
- Preserve user manual edits — if the file changes between turns, treat those changes as intentional and don't revert without asking.
