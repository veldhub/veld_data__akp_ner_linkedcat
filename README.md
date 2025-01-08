# NER Inference on linkedcat data from solr

This repo contains machine inferenced named entities and some context data. The inference was done 
by self-trained spaCy NER models, and applied on linkedcat SOLR data. There are two datasets on 
Solr: `linkedcat` (older) and `linkedcat2` (more recent and bigger). 

The inference veld chain, which produced this data repo can be found here: 
https://github.com/veldhub/veld_chain__akp_ner_inference

The models were trained here:
https://github.com/veldhub/veld_chain__train_spacy_apis_ner

The respective VELD metadata can be found at [./linkedcat/linkedcat.csv](./linkedcat/linkedcat.csv) 
and at [./linkedcat2/linkedcat2.csv](./linkedcat2/linkedcat2.csv) .

