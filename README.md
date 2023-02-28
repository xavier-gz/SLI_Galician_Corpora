# SLI Galician Corpora
## Corpora for Galician language

These resources are made available under the terms of Creative Commons Attribution 4.0 International Public License (CC BY 4.0) (which you can find at https://creativecommons.org/licenses/by/4.0/), and are distributed without any warranty.

Information and contact: Xavier Gómez Guinovart (xgg2021@gmail.com)

|File|Size|Description|
|----|-----|-------|
|SLI_CLUVI_EN_GL_TMX_3.4|19.7M|Engish-Galician sentence-level translation pairs (291,633 translated sentences) from the _CLUVI Corpus_ (https://ilg.usc.gal/cluvi/) in XML TMX (Translation Memory eXchange) format|
|SLI_CLUVI_ES_GL_TMX_3.4|30.7M|Spanish-Galician sentence-level translation pairs (318,863 translated sentences) from the _CLUVI Corpus_ (https://ilg.usc.gal/cluvi/) in XML TMX (Translation Memory eXchange) format|
|SLI_CLUVI_LEGA_TMX_2.1.tar.gz|9.8M|_LEGA Parallel Corpus_ of Galician-Spanish legal texts (6,582,415 words) at version 2.1 (https://ilg.usc.gal/cluvi/) in XML TMX (Translation Memory eXchange) format|
|SLI_NERC_Galician_Gold_CoNLL.1.0.tar.gz|460K|_SLI NERC Galician Gold Corpus_ encoded in CoNLL format for machine learning in tasks of Named Entity Recognition and Classification|
|SLI_NERC_Galician_Gold_FreeLing.1.0.tar.gz|1.7M|_SLI NERC Galician Gold Corpus_ encoded in FreeLing format for machine learning in tasks of Named Entity Recognition and Classification|
|SLI_CTG_POS.1.1.tar.gz|2.9M|_CTG Galician Technical Corpus_ (http://ilg.usc.gal/ctg/) tagged with POS for machine learning and used for training by the _IXA pipes_ tools (http://ixa2.si.ehu.es/ixa-pipes)|
|SLI_CTG_Lemma.1.0.tar.gz|3.2M|_CTG Galician Technical Corpus_ (http://ilg.usc.gal/ctg/) lemmatised for machine learning and used for training by the _IXA pipes_ tools (http://ixa2.si.ehu.es/ixa-pipes)|
|SLI_CTG_POS_Lemma.1.1.tar.gz|3.9M|_CTG Galician Technical Corpus_ (http://ilg.usc.gal/ctg/) tagged with POS and lemmas for machine learning|
|SLI_GalWeb.1.0.tar.gz|302M|_SLI GalWeb Corpus_ is a large corpus for Galician (174.630.824 words) compiled by the SLI from various domains by crawling for machine learning and used for training by the _IXA pipes_ tools (http://ixa2.si.ehu.es/ixa-pipes)|

***
## Note 1

***SLI_CLUVI_ES_GL_TMX_3.4*** has been split into 25MB parts with the _split_ command:

```console
$ split -b 25M -d SLI_CLUVI_ES_GL_TMX_3.4.tar.gz SLI_CLUVI_ES_GL_TMX_3.4.tar.gz.part
```

To rejoin these parts after download, you can use the _cat_ command:

```console
$ cat SLI_CLUVI_ES_GL_TMX_3.4.tar.gz.part* > SLI_CLUVI_ES_GL_TMX_3.4.tar.gz
```

## Note 2

**SLI_GalWeb.1.0.tar.gz** has been split into 25MB parts with the _split_ command:

```console
$ split -b 25M -d SLI_GalWeb.1.0.tar.gz SLI_GalWeb.1.0.tar.gz.part
```

To rejoin these parts, you can use the _cat_ command:

```console
$ cat SLI_GalWeb.1.0.tar.gz.part* > SLI_GalWeb.1.0.tar.gz
```
