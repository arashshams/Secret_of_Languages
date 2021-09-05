# Secret of Languages
This repo hosts a visual analysis of 17 different spoken languages in the world.

For more details, please refer to the [Kaggle Kernel](https://www.kaggle.com/arashshamseddini/secret-of-languages/).

In this analysis, I will visually demonstrateb how these langaues are different is certain attributes.

## Datasets
There are two data sets used in this study (found here), the `Languages` and the `Spoken texts` data sets.

Below is a sneak peek at both datas sets following with an overview of features in each.

### image

<center><h3>Languages dataset</h4></center>

| Column              | Description                                       |
|---------------------|---------------------------------------------------|
| iso_lang            | ISO_639-3 language code                           |
| language            | Language name                                     |
| information density | Bits of information per syllable in the language  |
| distinct_syllables  | The number of different syllables in the language |
| continent           | The continent where the language is spoken        |

### image

<center><h3>Spoken texts dataset</h4></center>

| Column    | Description                                     |
|-----------|-------------------------------------------------|
| speaker   | Speaker ID                                      |
| iso_lang  | ISO_639-3 language code                         |
| text      | Text ID                                         |
| sex       | The sex of the speaker                          |
| duration  | The number of seconds it took to speak the text |
| syllables | Number of syllables uttered during the speech   |
| age       | The age of the speaker                          |

The following plot shows how the trend that explains the relation between `information_density` and `distinct_syllables` divides the whole bunch into two clusters. It is worth-mentioning that **French** and **Mandarin** are outliers in each cluster.

### image

Once speech_rate as defined below:


is plotted against information_density, a subtle point is found. Technically, a high value in both features (information_density & speech_rate) would indicate a high information rate and efficient communication (a higher number of information bits conveyed per second).
