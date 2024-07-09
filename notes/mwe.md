# Course 2: MWE annotation

## Lecture 1 
- [slides](https://docs.google.com/presentation/d/1pb83jk2FAvQko88mQ24POaF2oncr0UhcWOR9wXDwWKg/) (with interactively added multilingual examples)


### Definitions 
MWE =
  - sequence of words that acts as a single unit at some level of linguistic analysis (Calzolari et al. 2002)
  - lexical item that
    - can be decomposed into multiple lexemes
    - display lexical, syntactic, semantic, pragmatic... idiomaticity
    - combination of at least 2 words that echibit idiosyncrasies at various linguistic levels (most prominently, semantic non-compositionality)
- types of idiosyncrasies:
  - lexical
  - morphological
  - syntactical
  - semantical
  - pragmatical
- MWEs $\neq$ collocations (the latter is a statistical concepts) 
  > yet, for something to be a MWE it has to be established - but what about the cases where they serve me a _cold dog_ (=cold hot dog)?

### MWEs in NLP
- tasks:
  - discovery (text $\to$ lexicon, typically with a human in the loop)
  - identification (text $\to$ annotated text)
- challenges:
  - statistical measures are not always effective (cf. frequent but non idiosyncratic expressions)
  - distance between constituents can be long
  - overlapping MWEs:
    - factorization
    - nesting
- methods:
  - rule-based
  - statistical
  - trad. ML-based
  - deep learning-based
