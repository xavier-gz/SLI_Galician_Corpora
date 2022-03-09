# SLI Galician Corpora
## Corpora for Galician language

|File|Size|Description|
|----|-----|-------|     
|SLI_CLUVI_LEGA_TMX_2.1.tar.gz|9.8M|_LEGA Parallel Corpus_ of Galician-Spanish legal texts (6,582,415 words) at version 2.1 (http://sli.uvigo.gal/CLUVI) in _XML TMX (Translation Memory eXchange)_ format|
|SLI_NERC_Galician_Gold_CoNLL.1.0.tar.gz|460K|_SLI NERC Galician Gold Corpus_ encoded in _CoNLL_ format for machine learning in tasks of Named Entity Recognition and Classification|
|SLI_NERC_Galician_Gold_FreeLing.1.0.tar.gz|1.7M|_SLI NERC Galician Gold Corpus_ encoded in _FreeLing_ format for machine learning in tasks of Named Entity Recognition and Classification|
|SLI_CTG_POS.1.0.tar.gz|2.6M|_CTG Galician Technical Corpus_ (http://sli.uvigo.gal/CTG) tagged with POS for machine learning and used for training by the _IXA pipes_ tools (http://ixa2.si.ehu.es/ixa-pipes)|
|SLI_CTG_Lemma.1.0.tar.gz|3.2M|_CTG Galician Technical Corpus_ (http://sli.uvigo.gal/CTG) lemmatised for machine learning and used for training by the _IXA pipes_ tools (http://ixa2.si.ehu.es/ixa-pipes)|
|SLI_GalWeb.1.0.tar.gz|302M|_SLI GalWeb Corpus_ is a large corpus for Galician (174.630.824 words) compiled by the SLI from various domains by crawling for machine learning and used for training by the _IXA pipes_ tools (http://ixa2.si.ehu.es/ixa-pipes)|

These resources are made available under the terms of Creative Commons Attribution 4.0 International Public License (CC BY 4.0) (which you can find at https://creativecommons.org/licenses/by/4.0/), and are distributed without any warranty.

Information and contact: Xavier Gómez Guinovart (xgg2021@gmail.com)

***
## Note

***SLI_GalWeb.1.0.tar.gz*** file has been split into 25MB parts with the split command:

```console
$ split -b 25M -d SLI_GalWeb.1.0.tar.gz SLI_GalWeb.1.0.tar.gz.part
```

To rejoin these parts, you can use the cat command:

```console
$ cat SLI_GalWeb.1.0.tar.gz.part* > SLI_GalWeb.1.0.tar.gz
```
