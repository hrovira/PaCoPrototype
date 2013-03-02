PaCoPrototype
=============

Parallel Coordinates Prototype is a simple HTML web application using D3.js.  

Deploy in any web content container using the following directory structure:
  - index.html (can be renamed)
  - css/parallel_coordinates.css
  - data/variants.tsv
  - data/samples.tsv

Schema
=============
variants.tsv

Gene | String | Must match gene in samples.tsv
Coordinate | String | e.g. chr7:123456789
MAF(%) | Decimal | e.g. 0.01
Polyphen2 prediction | Decimal | e.g. 0.01
Gene Function | String | 
Minor Allele Transmitted | String | 
Major Allele Transmitted | String | 
EUR | Decimal | Admixture Ratio 
ASN | Decimal | Admixture Ratio 
AFA | Decimal | Admixture Ratio 
AMR | Decimal | Admixture Ratio 
