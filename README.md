# FAIR-Data-Engineering-Group-17

This repository consists of the data, reconciled FAIRified data and the metadata of the dataset (https://www.kaggle.com/datasets/nilimajauhari/glassdoor-analyze-gender-pay-gap/data) containing data collected from the Glassdoor website regarding the remuneration of various employees based on gender, seniority, education, department, performance evaluation etc.

## Repository contents

### `data/` 
- **Glassdoor-Gender-Pay-Gap.csv** : contains the raw data taken directly from kaggle.
- **Glassdoor-Gender-Pay-Gap-enriched.csv** : contains the reconciled data after matching its elements with its appropriate wikibase counterparts.

### `metadata/`
- metadata generated from the fairdatapoint tool for the dataset, the distribution and the catalog containing them.

### `ontology/`
- **Glassdoor_data_protege_ontology.owx** : owl format ontology created from Protégé for the dataset.
- **ontograf.png** : ontograf diagram generated in Protégé.

### `rdf/`
- **Glassdoor_data_openrefine.ttl** - RDF export from openrefine.
- **Glassdoor_data_protege.ttl** - RDF export from Protégé.
