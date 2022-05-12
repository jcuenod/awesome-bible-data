# Awesome Bible Datasets ![Awesome](https://awesome.re/badge-flat2.svg)

Welcome! This is a curated list of data related to biblical research. For this reason it includes not only translations but tagged original language corpora as well as datasets that are Bible-adjacent (such as early church writings, and dictionaries).

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
- [Dictionaries](#dictionaries)
- [Cross References](#cross-references)

## Datasets

### Protestant Canon

#### Translations

  - [Parallel corpora from eBible.org](https://github.com/BibleNLP/ebible-corpus) (Verse per line txt). [source](https://eBible.org). - Made for use with NLP, not ideal for finding book/ch/v divisions.
  - [Gratis Bible](https://github.com/gratis-bible/bible) (OSIS XML)
  - [Open English Bible](https://github.com/openenglishbible/Open-English-Bible) - A Bible translation is in the public domain(?)
  - [Unfolding Word Translations](https://git.door43.org/unfoldingWord/) - See esp. their [Literal Translation](https://git.door43.org/unfoldingWord/en_ult/), [Simplified Translation](https://git.door43.org/unfoldingWord/en_ust/). Resources developed for Bible translators.

#### Original Languages

  **OT**
  - [MorphHB](https://github.com/openscriptures/morphhb/) [🏷️](## "Morphologically Tagged") - Crowd sourced tagging of the OT
  - [ETCBC BHSa](https://github.com/ETCBC/bhsa) (TextFabric) [🌲](## "Syntax Trees") [🏷️](## "Morphologically Tagged")
  - [Macula Hebrew](https://github.com/Clear-Bible/macula-hebrew/) [🌲](## "Syntax Trees") - One of the most developed datasets. Combines multiple sources, with clear provenance!
  - [STEPBible Data](https://github.com/STEPBible/STEPBible-Data) [🏷️](## "Morphologically Tagged") - One of the most developed datasets
  - [Peshitta](https://github.com/ETCBC/peshitta) (TextFabric)

  **LXX**
  - [CCAT LXX](https://github.com/orenfromberg/lxxproject) in sqlite [🏷️](## "Morphologically Tagged")
  - [STEPBible Data](https://github.com/STEPBible/STEPBible-Data) [🏷️](## "Morphologically Tagged") - one of the most developed datasets
  - [Swete's LXX](https://github.com/sleeptillseven/LXX-Swete/) Text from 1KY corrected [🏷️](## "Morphologically Tagged")
  - [LXX Codex Alexandrinus](https://github.com/sleeptillseven/LXX.Alex)
  
  **NT**
  - [SBLGNT Tagged by MorphGNT](https://github.com/morphgnt/sblgnt) [🏷️](## "Morphologically Tagged")
  - [Byzantine Majority Text](https://github.com/byztxt/byzantine-majority-text) [🏷️](## "Morphologically Tagged")
  - [NA1904 Tagged by MorphGNT](https://github.com/biblicalhumanities/Nestle1904/) [🏷️](## "Morphologically Tagged")
  - [Macula Greek](https://github.com/Clear-Bible/macula-greek) [🌲](## "Syntax Trees") [🏷️](## "Morphologically Tagged") - One of the most developed datasets. Combines multiple sources, with clear provenance!
  - [STEPBible Data](https://github.com/STEPBible/STEPBible-Data) [🏷️](## "Morphologically Tagged") - One of the most developed datasets!
  - [Bunning Heuristic Prototype Greek New Testament](https://github.com/greekcntr/BHP) - An approach to construct a critical NT based on the earliest evidence
  - [Syriac New Testament](https://github.com/etcbc/syrnt) (TextFabric)
  - [Levinsohn's Greek New Testament Discourse Features](https://github.com/biblicalhumanities/levinsohn) [💬](## "Discourse Analysis")
  - [PROIEL Treebanks](https://github.com/proiel/proiel-treebank) (GNT, Vulgate, other NTs + more) [🌲](## "Syntax Trees")
  - [SBLGNT and Nestle1904](https://github.com/biblicalhumanities/greek-new-testament) with syntax trees by the Global Bible Initiative [🌲](## "Syntax Trees") [🏷️](## "Morphologically Tagged")
  
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
  - (Greek) [Apostolic Fathers](https://github.com/jtauber/apostolic-fathers) hand corrected.
  - (Greek) [Justin Martyr](https://github.com/Mallioch/justin-martyr-texts)
  - (Greek) [Clement of Alexandria](https://github.com/Mallioch/clement-of-alexandria-texts)
  - (English) [Ante- and Post-Nicene Fathers](https://github.com/gregorycrane/nicenefathers) (TEI XML)
  - (Greek) [Patristics](https://github.com/pthu/patristics) (TextFabric)

### Dictionaries

- [Jastrow/Klein Dictionaries](https://github.com/Sefaria/Sefaria-Data/tree/master/lexicon)
- [Strongs](https://github.com/openscriptures/strongs) (OT + NT)
- [BDB](https://github.com/openscriptures/HebrewLexicon) (OT)
- [Abbott-Smith](https://github.com/translatable-exegetical-tools/Abbott-Smith) (NT)
- [Jeffrey Dodson's Greek Lexicon](https://github.com/biblicalhumanities/Dodson-Greek-Lexicon) (NT)

### Cross References

- https://github.com/balinjdl/OT-NT-Reference-Map
- https://github.com/josephilipraja/bible-cross-reference-json
- https://github.com/SuzanaK/bible_cross_references
