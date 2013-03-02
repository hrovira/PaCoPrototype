PaCoPrototype
=============

Parallel Coordinates Prototype is a simple HTML web application using D3.js.

Deploy in any web content container using the following directory structure:
  - index.html (can be renamed)
  - data/variants.tsv
  - data/samples.tsv

Schema :: data/variants.tsv
============
| Column | Type | Description |
| --------- | ---------- |------------ |
| Gene | String | Must match gene in samples.tsv |
| Coordinate | String | e.g. chr7:123456789 |
| MAF(%) | Decimal | e.g. 0.01 |
| Polyphen2 prediction | Decimal | e.g. 0.01 |
| Gene Function | String | |
| Minor Allele Transmitted | String | |
| Major Allele Transmitted | String | |
| EUR | Decimal | Admixture Ratio |
| ASN | Decimal | Admixture Ratio |
| AFA | Decimal | Admixture Ratio |
| AMR | Decimal | Admixture Ratio |

Schema :: data/samples.tsv
============
| Column | Type | Description |
| --------- | ---------- |------------ |
| Gene | String | Must match gene in variants.tsv |
| SampleID | String | Accepts any number of arbitrary columns |
| EUR | Decimal | Admixture Ratio |
| ASN | Decimal | Admixture Ratio |
| AFA | Decimal | Admixture Ratio |
| AMR | Decimal | Admixture Ratio |
