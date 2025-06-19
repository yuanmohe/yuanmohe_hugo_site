---
title: The Complexity of Measuring Music Complexity
summary: A project at the Complex Systems Summer School 2023 
# tags:
#   - NLP
date: -3

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
commentable: false  # Show comments?

---
We introduce the use of image compression to analyze the complexity of an artist’s discography over time. The ratio of a compressed file size to the size of the raw file is a proxy for the entropy in the file. We can represent a song as an image using chromographs, which bins the frequencies in the song into the twelve pitches in the Western musical scale and show the intensity for each pitch as a function of time. We chose to focus on one well-known musical group, The Beatles, as a case study for proof of concept. While the mean entropy across songs in each album did not vary significantly over time, the standard deviation in entropy increased over time. We apply the same compression algorithm to quantify the similarity between songs. Within-album song similarity shows a similar increase in standard deviation for later albums. The results do not indicate that songs that were released in close succession are more similar. In addition to this metric, we use the Diffusion Entropy Analysis to measure the complexity of pitch over time within a song. However, since this method does not include percussion, the results are different from those measured on the chromographs. We also measure the complexity of lyrics. We first use more established text complexity measures for lexical diversity and readability. Then we use the average Euclidean distance or cosine similarity of all the words in a song as a novel measure of the semantic complexity of the lyrics. The different measures correlate with each other. The mean text complexity, especially measured as the average semantic distance between words, appears to increase over time.

Authors: Cheyenne Jarman, Golnar Gharooni Fard, Virginia Domínguez-García, Faith Masibili, Yuanmo He, Joris Bücker, Annie Stephenson (Equal contribution led by the first author.)
