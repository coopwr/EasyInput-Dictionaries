# Easy Input Dictionaries

Public, offline SQLite dictionaries for Spanish, English, Mandarin Chinese (both scripts), French, Arabic, German, Russian and Italian. Definitions are in English. This repository contains no app source, credentials, transcripts or personal vocabulary.

## Downloads

Use the versioned GitHub Release assets. Each language has a JSON manifest with its exact byte size, SHA-256 hash and immutable SQLite filename. Verify the hash before installation. These are data files, not executables. The app downloads languages individually and retains them for offline use.

## Attribution and license

Dictionary data is redistributed under **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**. See LICENSE.txt and https://creativecommons.org/licenses/by-sa/4.0/ . No additional restrictions are imposed. No upstream contributor endorses this project.

- English Wiktionary contributors: https://en.wiktionary.org/ . Every Wiktionary entry retains a source_url linking to its original article; article history credits its contributors. Copyright terms: https://en.wiktionary.org/wiki/Wiktionary:Copyrights . Data was extracted by Wiktextract and provided by Kaikki: https://kaikki.org/dictionary/ . Kaikki extraction credits: https://kaikki.org/ . Wiktionary also offers its text under GFDL; this distribution uses the CC BY-SA option.
- Chinese pack additionally includes **CC-CEDICT contributors**, CC BY-SA 4.0: https://www.mdbg.net/chinese/dictionary?page=cc-cedict . Simplified and traditional keys and pinyin are retained. CC-CEDICT rows retain their source attribution.

## Changes and provenance

Packs prepared 2026-10-14 from the official English-edition Kaikki per-language JSONL downloads (Chinese plus Mandarin for zh) and CC-CEDICT. This is a transformed/filtered version, not an unmodified upstream dump: English glosses, part of speech, pronunciation and source links are converted to read-only SQLite; lookup keys are Unicode NFC, non-Chinese/non-Arabic keys are lowercase; duplicate senses are removed; CC-CEDICT entries are indexed under both scripts. No images, usage examples or audio are redistributed.

Exact-form coverage varies, especially Arabic vocalization and inflections. Entries are not guaranteed complete or correct. Pack sizes and integrity information are in the manifests. Release versions are immutable; publish a new version for updates.
