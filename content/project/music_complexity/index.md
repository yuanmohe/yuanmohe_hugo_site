---
title: Music Complexity
summary: Project at the Complex Systems Summer School 2023 
# tags:
#   - NLP
date: -3

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
commentable: false  # Show comments?

---
In this project we introduced the application of image compression analysis to assess the complexity of an artist’s discography via chromograms, which provide chroma-based audio features useful for analyzing, comparing and processing music data. In our first case study, The Beatles, we found that the mean entropy across songs in each album was relatively stable over time. However, the standard deviation more than quadrupled (Fig. 1). We also assessed within-album song similarity and found a similar trend, suggesting that songs that were released in close succession are not necessarily more similar. We also evaluated the lyrical complexity of the same set of songs by calculating the average semantic distance between the words. We found that the mean text complexity among the Beatles’ albums increased over time. Although audio and lyrics complexity are not correlated for individual songs, the similar trends between how audio and lyrics complexity change over time point to the robustness of our approach. Finally, we also quantified the complexity of the harmony of the songs using the music network library developed by Nardelli et al., 2022. The diffusion entropy analyses revealed that the complexity of the harmony is negatively correlated with the complexity via chromogram (Fig. 2), probably because the harmony analysis does not take into consideration the percussion instruments.
