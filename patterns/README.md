This project uses lexical and phonological data from four language families, sourced from the North Eurasian Lexicostatistical Database (NorthEuraLex). The dataset is provided in two .tsv files:
- languages.tsv: Contains metadata about the languages in the sample (indexed by ISO codes), including language family and inventory size.
- forms.tsv: Includes lexical entries for hundreds of concepts across the languages, along with derived phonological metrics such as:
  - Word length (in segments)
  - Longest consonant cluster length per word
  - Vowel-to-consonant ratio (smoothed)
    
These features are used to explore phonological patterns, compare language families, and build predictive models.
