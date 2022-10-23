***SLI_CLUVI_ES_GL_TMX_3.4*** has been split into 25MB parts with the _split_ command:

```console
$ split -b 25M -d SLI_CLUVI_ES_GL_TMX_3.4.tar.gz SLI_CLUVI_ES_GL_TMX_3.4.tar.gz.part
```

To rejoin these parts after download, you can use the _cat_ command:

```console
$ cat SLI_CLUVI_ES_GL_TMX_3.4.tar.gz.part* > SLI_CLUVI_ES_GL_TMX_3.4.tar.gz
```


***SLI_CLUVI_ES_GL_TMX_3.4***

Spanish-Galician sentence-level translation pairs (318,863 translated sentences) from the CLUVI Corpus (https://ilg.usc.gal/cluvi/) in XML TMX (Translation Memory eXchange) format. The CLUVI Corpus is an collection of human-annotated sentence-level aligned parallel corpora developed by the SLI at the University of Vigo and originally designed to cover specific areas of the contemporary Galician language in relation to other languages. With over 49 million words, the CLUVI collection currently comprises twenty-three parallel corpora in nine specialised registers or domains (fiction, computing, popular science, biblical texts, law, consumer information, economy, tourism, and film subtitling) and different language combinations with Galician, Spanish, English, French, Brazilian Portuguese, European Portuguese, Catalan, Italian, Basque, German, Latin, Simplified Chinese and Traditional Chinese.

Sentence pairs in this dataset are both randomly shuffled and anonymized. The dataset is mainly designed for academic research in natural language processing and machine translation training, but also can be used in other multilingual NLP tasks.

This resource is made available at no cost under the terms of Creative Commons Attribution 4.0 International Public License (CC BY 4.0) (which you can find at https://creativecommons.org/licenses/by/4.0/), and is distributed without any warranty.

Please give an appropriate acknowledgement if you publish work containing results derived from use of this resource.

Gómez Guinovart, Xavier (2019): Enriching parallel corpora with multimedia and lexical semantics: From the CLUVI Corpus to WordNet and SemCor. In Irene Doval e M. Teresa Sánchez Nieto (eds.), _Parallel Corpora for Contrastive and Translation Studies: New resources and applications_ (ISBN 978-90-272-0234-5), John Benjamins, Amsterdam, pp. 141-158. DOI: https://doi.org/10.1075/scl.90.09gom

