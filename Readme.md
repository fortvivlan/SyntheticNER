# SyntheticNER

###Last commit updates:

- added George Washington to PER names (also fixed Turkish Vaşington for LOC Nominative)
- updated PER contexts (fix bugs and людина)
- added LOC names for Locative case (no ca and es!)
- LOC contexts for Locative, however, contain all languages, joker slot is '[???]'
- LOC names for Accusative or Dative case: only for be, en, ru and tr (be and ru in Acc, en in Nom, tr in Dat)
- LOC contexts for Acc or Dat case are also only for be, en, ru and tr.  Joker slot is '[???]', the names and the contexts take into account the presence of prepositions (you simply have to paste a name)

Conventions are as follows:

PER names - PERson names in Nominative <br />
PER sents - contexts for PERson names in Nominative ('m' or 'f' slots) <br />
LOC_NOM names - LOCation names in Nominative <br />
LOC_NOM sents - contexts for LOCations in Nominative ('[???]' slots) <br />
LOC_ACC_DAT names - LOCation names in Accusative for be and ru, Nominative for en and Dative for tr <br />
LOC_ACC_DAT sents - contexts for the above ('[???]' slots) <br />
LOC_LOC names - LOCation names in Locative <br />
LOC_LOC sents - LOCation contexts for the above ('[???]' slots) <br />
ORG names - ORGanizations (Nominative, no gender or number disambiguation) <br />
ORG contexts - respective contexts ('[???]' slots) <br />