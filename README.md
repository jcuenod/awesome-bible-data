# Awesome Bible Data ![Awesome](https://awesome.re/badge-flat2.svg)

Biblical data including translations, tagged original language texts, second temple literature, early church writings, dictionaries, and cross references.

**Legend**:

 - 🏷️  Morphologically Tagged
 - 🌲 Syntax Trees
 - 💬 Discourse Analysis

## Contents

- [Protestant Canon](#protestant-canon)
  - [Translations](#translations)
  - [Original Languages](#original-languages)
- [Non-Canonical](#non-canonical)
  - [Deuterocanonical](#deuterocanonical)
  - [Qumran/Rabbinic](#qumranrabbinic)
  - [Early Church](#early-church)
- [Versification Mappings](#versification-mappings)
- [Dictionaries](#dictionaries)
  - [Other Language Dictionaries](#other-languages-dictionaries)
- [Cross References](#cross-references)

## Data

### Protestant Canon

#### Translations

  - [Bible corpus](https://github.com/christos-c/bible-corpus) - A multilingual parallel corpus created from translations of the Bible.
  - [Gratis Bible](https://github.com/gratis-bible/bible) (OSIS XML)
  - [Open English Bible](https://github.com/openenglishbible/Open-English-Bible) - A CC0 Bible translation.
  - [Parallel corpora from eBible.org](https://github.com/BibleNLP/ebible-corpus) (Verse per line txt). [source](https://eBible.org). - Made for use with NLP, not ideal for finding book/ch/v divisions.
  - [Unfolding Word Translations](https://git.door43.org/unfoldingWord/) - See esp. their [Literal Translation](https://git.door43.org/unfoldingWord/en_ult/), [Simplified Translation](https://git.door43.org/unfoldingWord/en_ust/). Resources developed for Bible translators.
  - [Zefania Bibles](https://sourceforge.net/projects/zefania-sharp/) - A corpus of 140+ Bibles in 63 languages (and some English/German resources such as concordances). The Bibles are formatted in "Zefania XML". Some include strongs tagging.
  - [Aligned Bible Texts](https://github.com/Clear-Bible/Alignments), automatic and/or manually corrected.

#### Original Languages

  **OT**
  - [ETCBC BHSa](https://github.com/ETCBC/bhsa) (TextFabric) [🌲](## "Syntax Trees") [🏷️](## "Morphologically Tagged")
  - [Macula Hebrew](https://github.com/Clear-Bible/macula-hebrew/) [🌲](## "Syntax Trees") - One of the most developed datasets. Combines multiple sources, with clear provenance!
  - [MorphHB](https://github.com/openscriptures/morphhb/) [🏷️](## "Morphologically Tagged") - Crowd sourced tagging of the OT
  - [Peshitta](https://github.com/ETCBC/peshitta) (TextFabric)
  - [STEPBible Data](https://github.com/STEPBible/STEPBible-Data) [🏷️](## "Morphologically Tagged") - One of the most developed datasets
  - [Speaker Quotations](https://github.com/Clear-Bible/speaker-quotations) for the whole Bible in various translations and the original languages. [💬](## "Discourse Analysis")

  **LXX**
  - [CCAT LXX](https://github.com/orenfromberg/lxxproject) in sqlite [🏷️](## "Morphologically Tagged")
  - [LXX Codex Alexandrinus](https://github.com/sleeptillseven/LXX.Alex)
  - [STEPBible Data](https://github.com/STEPBible/STEPBible-Data) [🏷️](## "Morphologically Tagged") - Appears to only be available upon request
  - [Swete's LXX](https://github.com/sleeptillseven/LXX-Swete/) Text from 1KY corrected [🏷️](## "Morphologically Tagged")

  **NT**
  - [Byzantine Majority Text](https://github.com/byztxt/byzantine-majority-text) [🏷️](## "Morphologically Tagged")
  - [SBLGNT](https://github.com/LogosBible/SBLGNT) - Source data for the SBL GNT published by Logos.
  - [SBLGNT Tagged by MorphGNT](https://github.com/morphgnt/sblgnt) [🏷️](## "Morphologically Tagged")
  - [Levinsohn's Greek New Testament Discourse Features](https://github.com/biblicalhumanities/levinsohn) [💬](## "Discourse Analysis")
  - [Macula Greek](https://github.com/Clear-Bible/macula-greek) [🌲](## "Syntax Trees") [🏷️](## "Morphologically Tagged") - One of the most developed datasets. Combines multiple sources, with clear provenance!
  - [NA1904 Tagged by MorphGNT](https://github.com/biblicalhumanities/Nestle1904/) [🏷️](## "Morphologically Tagged")
  - [PROIEL Treebanks](https://github.com/proiel/proiel-treebank) (GNT, Vulgate, other NTs + more) [🌲](## "Syntax Trees")
  - [SBLGNT and Nestle1904](https://github.com/biblicalhumanities/greek-new-testament) with syntax trees by the Global Bible Initiative [🌲](## "Syntax Trees") [🏷️](## "Morphologically Tagged")
  - [Statistical Restoration GNT](https://github.com/Center-for-New-Testament-Restoration/SR)  [🏷️](## "Morphologically Tagged") - An approach to construct a critical NT based on the earliest evidence (was Bunning Heuristic Prototype GNT)
  - [STEPBible Data](https://github.com/STEPBible/STEPBible-Data) [🏷️](## "Morphologically Tagged") - One of the most developed datasets!
  - [Syriac New Testament](https://github.com/etcbc/syrnt) (TextFabric)
  - [OpenText Context Annotations](https://github.com/OpenText-org/context-annotation) extracted from forthcoming OpenText 2.0 syntax data, these include pericopes, speaker turns (maps to Speaker Quotations dataset above), moves within turns, and tokens/expressions for mapping to other datasets. [💬](## "Discourse Analysis")[🌲](## "Syntax Trees")

### Non-Canonical
#### Deuterocanonical
  - [Online-Critical-Pseudepigrapha](https://github.com/OnlineCriticalPseudepigrapha/Online-Critical-Pseudepigrapha) - multiple versions of the Pseudepigrapha, powering <http://pseudepigrapha.com>
  - (English) https://github.com/scrollmapper/bible_databases_deuterocanonical
  - (English/Hebrew) https://github.com/Sefaria/Sefaria-Export

#### Qumran/Rabbinic
  - https://github.com/ETCBC/dss (TextFabric) [🏷️](## "Morphologically Tagged")
  - https://github.com/ETCBC/extrabiblical
  - https://github.com/Sefaria/Sefaria-Export

#### Early Church
  - (English) [Ante- and Post-Nicene Fathers](https://github.com/gregorycrane/nicenefathers) (TEI XML)
  - (Greek) [Apostolic Fathers](https://github.com/jtauber/apostolic-fathers) hand corrected.
  - (Greek) [Clement of Alexandria](https://github.com/Mallioch/clement-of-alexandria-texts)
  - (Greek) [Justin Martyr](https://github.com/Mallioch/justin-martyr-texts)
  - (Greek) [Patristics](https://github.com/pthu/patristics) (TextFabric)

### Versification Mappings
 - [CCEL Reference Mappings](https://github.com/adamb924/references-in-sqlite) - Converted to sqlite. Note, the original mappings are no longer at the CCEL URL.
 - [Copenhagen Alliance Versification Mappings](https://github.com/Copenhagen-Alliance/copenhagen-alliance.github.io/tree/master/specifications/versification)
 - [STEPBible TVTMS](https://github.com/STEPBible/STEPBible-Data) - Translators Versification Traditions with Methodology for Standardisation

### Dictionaries

- [Abbott-Smith](https://github.com/translatable-exegetical-tools/Abbott-Smith) (NT)
- [BDB](https://github.com/openscriptures/HebrewLexicon) (OT)
- [Jeffrey Dodson's Greek Lexicon](https://github.com/biblicalhumanities/Dodson-Greek-Lexicon) (NT)
- [Koine Greek English Dictionary](https://github.com/biblical-text/koine-greek-english-dictionary) CC0. Updated Strongs (likely only NT Greek).
- [Strongs](https://github.com/openscriptures/strongs) (OT + NT)

#### Other Language Dictionaries

- [Koine Greek to Chinese Dictionary](https://github.com/biblical-text/koine-greek-chinese-dictionary) CC0. Apparently a conversion of the "Koine Greek English Dictionary" to Chinese. Because it's strongs based, likely only NT Greek. "This dictionary contains Chinese glosses where a gloss is available from the biblical text database."

### Cross References

- https://github.com/balinjdl/OT-NT-Reference-Map
- https://github.com/josephilipraja/bible-cross-reference-json
- https://github.com/SuzanaK/bible_cross_references
