# candigingestschema

This was the files that relate to CanDIGv2 data ingest. 

test data issue was from the tests/katsu_ingest.py which failed in the validation when run the ingest scripts:



`python katsu_ingest.py --input tests/clinical_ingest.json`


```
(candig) [rocky@candig-testing candigv2-ingest]$ pwd
/home/rocky/CanDIGv2/lib/candig-ingest/candigv2-ingest
(candig) [rocky@candig-testing candigv2-ingest]$ tree tests/
tests/
├── BAK-clinical_ingest.json
├── BAK-genomic_ingest.json
├── clinical_ingest.json
├── genomic_ingest.json
├── __init__.py
└── test_ingest.py

0 directories, 6 files

python katsu_ingest.py --input tests/clinical_ingest.json

```
