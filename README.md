# EXO's lyrics insights

## Overview
This project provides a detailed lyrical analysis of three EXO albums: "EXIST" (2023), "LOVE SHOT" (2018, a repackage of "Don't Mess Up My Tempo"), and "The War" (2017). The lyrics, originally composed in Korean, and the English translations of the lyrics were sourced from the Genius API, where translations for some of EXO's famous songs are available. These translations were extracted using Python, enabling a more accessible sentiment analysis and ensuring clarity for a global audience. This study employs natural language processing tools to explore word frequencies, emotional sentiments, and visual representations of lyrical themes through word clouds for each album.

## Data Preparation
English translations of the lyrics were extracted using Python from the Genius API. This step was crucial for applying NLP tools effectively without language constraints.

## Analysis Details

### Word Frequency Analysis
- **Most Frequent Words:** The word 'like' appeared most frequently across all albums, totaling 137 occurrences. In the "LOVE SHOT" album, 'la' was nearly as prevalent with 109 mentions, indicating its significance in this particular album.

### Sentiment Analysis
- **VADER Analysis:** VADER (Valence Aware Dictionary and sEntiment Reasoner) identifies not just the polarity (positive or negative) but also the intensity of sentiments. 'HAPPY' was the dominant sentiment across all albums, reflecting a generally positive tone.
- **NRC Analysis:** Using the NRC Emotion Lexicon, which classifies words into eight basic emotions and two sentiments, 'HAPPY' was also the predominant emotion. However, the "LOVE SHOT" album displayed a prevailing 'Negative' emotion, highlighting a contrast to the other albums.

### Album Contributions
- "LOVE SHOT" has a richer dataset with 13 songs, including 10 from its predecessor, "Don't Mess Up My Tempo," plus three new songs: "Love Shot," "Trauma," and "Wait." In comparison, the other two albums analyzed each contain 9 songs. This expanded song list in "LOVE SHOT" significantly enhanced the depth and variety of the dataset used in our analysis.
This revised wording accurately reflects the number of songs per album and underscores the importance of "LOVE SHOT" in the analysis due to its larger song count.

## Visual Representation
Word clouds for each album were generated to visually underscore the most prominent words, offering an intuitive understanding of the thematic and emotional nuances.

## Conclusion
The analysis reveals a predominant theme of happiness across EXO's albums, showcasing their ability to convey positive emotions through music. The distinct negativity in the "LOVE SHOT" album adds depth and complexity to the narrative, enriching the overall artistic portrayal. This study not only highlights recurrent themes but also illustrates the variability in emotional undertones across different albums, offering fans and researchers deeper insights into EXO's lyrical dynamics.
