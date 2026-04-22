# Mutual Intelligibility — English ↔ German

Personal pattern-based learning materials documenting where English and German cross over: cognates, sound shifts, shared loans, false friends, and Denglisch traps. Inspired pedagogically by *Madrigal's Magic Key to German* (1966) but rescoped to the broader concept of mutual intelligibility, modernized to post-1996 spelling, and stripped of basic-language instruction. This is not a textbook. It assumes the reader already knows the language basics from elsewhere.

## How this is organized

One markdown file per pattern. Each file collects all the words that fit that pattern, regardless of CEFR level. CEFR is an inline tag on each entry, not a structural axis. Files grow as the project mines higher levels.

## Scope and limits

**Bottom-up by CEFR.** A1 first (currently complete), then A2, B1, then above. Each pass adds entries to the relevant pattern files.

**Soft ceiling: top ~5,000 lemmas (~B2).** Pattern-relevant words above the ceiling are included when the pattern carries them.

**Sources serve as filters, not curricula.** The Goethe-Institut CEFR wordlists and the Madrigal book are inputs mined for cognate-pattern wins. Words that don't carry a cross-language pattern get skipped — even basic ones — except for function words (which DO get included because their Germanic kinship is a pattern in itself).

## Files

### Sound shifts (the High German consonant shift and friends)

- [shift-th-to-d.md](shift-th-to-d.md) — English *th* hardens to German *d*. The single highest-yield rule.
- [shift-t-to-ss-z.md](shift-t-to-ss-z.md) — English *t* between or after vowels becomes German *ss / ß / z*.
- [shift-k-to-ch.md](shift-k-to-ch.md) — English *k* between or after vowels becomes German *ch*.
- [shift-p-to-pf-ff.md](shift-p-to-pf-ff.md) — English *p* becomes German *pf* word-initial, *ff* medial.
- [shift-d-to-t.md](shift-d-to-t.md) — Final-position German *d* devoices to *t*; double *tt* after short vowels.
- [shift-gh-to-ch.md](shift-gh-to-ch.md) — English silent *gh* corresponds to German pronounced *ch*.

### Suffix patterns

- [suffix-ung.md](suffix-ung.md) — German *-ung* deverbal nouns, often map to English *-ation*, *-ing*, or unmarked.
- [suffix-er.md](suffix-er.md) — German agent *-er* maps to English *-er*.
- [suffix-lich.md](suffix-lich.md) — German *-lich* maps to English *-ly* or *-ish*.
- [suffix-isch.md](suffix-isch.md) — German *-isch* maps to English *-ic* / *-ical*.
- [suffix-tion.md](suffix-tion.md) — Identical *-tion* in both languages.
- [suffix-los.md](suffix-los.md) — German *-los* maps to English *-less*.
- [suffix-bar.md](suffix-bar.md) — German *-bar* maps to English *-able* or *-ful*.
- [suffix-itaet.md](suffix-itaet.md) — German *-ität* maps to English *-ity*. Emerges at A2, expands at B1.

### Surface relationships

- [identical-spelling-and-sound.md](identical-spelling-and-sound.md) — Words written the same way and pronounced almost identically.
- [sound-equivalent.md](sound-equivalent.md) — Words pronounced almost identically but spelled differently.
- [germanic-cognates-no-shift.md](germanic-cognates-no-shift.md) — Visible Germanic kinship without a named sound-shift rule.

### Shared vocabularies

- [loans-latin-greek-shared.md](loans-latin-greek-shared.md) — Scholarly vocabulary both languages borrowed from Latin or Greek.
- [loans-english-to-german.md](loans-english-to-german.md) — Denglisch: English words used in modern German.
- [loans-german-to-english.md](loans-german-to-english.md) — German words exported to English.
- [loans-international.md](loans-international.md) — Other international word families: Arabic, Italian, Slavic, Yiddish, Asian, etc.

### Warnings

- [warning-false-friends.md](warning-false-friends.md) — Words that look like English equivalents but mean something different.
- [warning-pseudo-anglicisms.md](warning-pseudo-anglicisms.md) — Words that look English but aren't used that way by English speakers.

### Function words

- [function-words.md](function-words.md) — Pronouns, prepositions, conjunctions, interrogatives. Pure grammar, but their Germanic kinship is itself a recognizable pattern.

## Entry format

Each entry uses this convention:

```
**english ↔ German** *(CEFR-level, optional grammatical or register notes)*
*German example sentence.*
```

For nouns, the German form includes its article (*der / die / das*).
For verbs, the German form is the infinitive.
Where the entry needs a usage note (false friend, regional variant, register), it gets a short prose line above or below the example. Example sentences are original to this project.

## Pronunciation conventions worth knowing

A few orthographic notes that aren't sound shifts but help with reading:

**German V is pronounced /f/.** *Vater* sounds like "FAH-ter." *Vier, viel, vor, von, voll* — all start with /f/. So when reading German, treat V as F. Where the etymological match exists, English F often corresponds to German V: *father / Vater*, *for / für*, *fore / vor*, *full / voll*, *four / vier*, *from / von*.

**German W is pronounced /v/.** *Wasser* sounds like "VAH-ser." So *was* = "vas," *wo* = "voh," *Wein* = "vine."

**German Z is pronounced /ts/.** *Zeit* sounds like "tsite." *Salz* ends with "-ts."

**German S between vowels is /z/.** *lesen* = "LAY-zen," *Sonne* = "ZON-uh."

**German -er at the end of a word is barely /-ɐ/, almost a vowel.** *Vater* = "FAH-tah."

These are the ones that flip a learner's expectations the most.

## Acknowledgments and references

This project draws on several external resources for guidance, validation, and CEFR-level filtering. The CC BY-SA license applies to the original analysis, pattern groupings, prose, and example sentences in this repository. Referenced source materials remain the property of their respective rights holders and are used here as references, not as content.

**Goethe-Institut wordlists.** The CEFR-tagged vocabulary scope is guided by the Goethe-Institut wordlists for Start Deutsch 1 (A1), Fit in Deutsch 1 (A1), Goethe-Zertifikat A2, and the joint Goethe / ÖSD B1 Wortliste, plus the *Deutsch-Test für Zuwanderer* (DTZ) wordlist. © Goethe-Institut and, where applicable, ÖSD.
https://www.goethe.de/

**Duden.** The authoritative reference for modern standard German spelling, gender, meaning, and usage labels. Used for per-word validation and for flagging dated or discriminatory terms.
https://www.duden.de/

**DWDS — Digitales Wörterbuch der deutschen Sprache.** Berlin-Brandenburgische Akademie der Wissenschaften. Used for lemma and frequency data as a free alternative to Duden for bulk work.
https://www.dwds.de/

**Wortschatz Leipzig (Leipzig Corpora Collection).** Leipzig University / Saxon Academy of Sciences. Reference corpus for frequency analysis.
https://wortschatz.uni-leipzig.de/

**Margarita Madrigal and Ursula Meyer, *Madrigal's Magic Key to German*** (Doubleday, 1966). Cited as pedagogical inspiration. The book's approach of teaching German through English cognate patterns is the direct ancestor of this project's organization, though the scope and treatment differ.

## Status

A1 and A2 mining complete. ~1,300 source words walked cumulatively, distributed into pattern files. B1 next. See git history and tags for milestones.

### Growth observations through A2

- The **Latin/Greek loan layer** and **English-to-German loans (Denglisch)** are the biggest growth vectors between A1 and A2. Scholarly and modern/technical vocabulary dominates.
- The ***-isch/-ic*** suffix pattern starts expanding at A2 (*fantastisch, praktisch, typisch, romantisch, komisch*) and will explode at B1 per Madrigal's observation.
- The ***-ität/-ity*** micro-pattern appears with *Qualität* and *Universität*, foreshadowing a rich B1 vein.
- **False friends multiply**: *aktuell, eventuell, sympathisch, komisch, fast* are all A2 traps. Especially *fast* — "almost," not "fast."
- **Function-word modifiers** (*besonders, eigentlich, plötzlich, wahrscheinlich, unbedingt*) appear at A2 and give German its nuance layer.

## License

Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). See the LICENSE file for full terms.
