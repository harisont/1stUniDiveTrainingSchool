# Lecture 1

## [Grew-match](https://universal.grew.fr/)

### Grew-match vs STUnD queries

| semantics | Grew-match | STUnD |
| --- | --- | --- |
| auxiliaries | `pattern { x[upos = AUX] }` | `UPOS "AUX"` |
| instances of "vara" used as auxiliaries | `pattern { x[upos = AUX, lemma = "vara"] }` | `AND [UPOS "AUX", LEMMA "vara"]` |
| copulas with nouns as complements | `pattern { X -[cop]->Y; X[upos = NOUN] }` | `TREE_ (UPOS "NOUN") [DEPREL "cop"]`

### Clustering
- [simple clustering](https://universal.grew.fr/?custom=668bfaea521cd)
- [double clustering](https://universal.grew.fr/?custom=668bfa38e1c93)

## [Arborator grew](arboratorgrew.elizia.ne)