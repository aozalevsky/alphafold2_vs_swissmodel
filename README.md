# alphafold2_vs_swissmodel

The repository keeps the code for the project on comparison of the AlphaFold2 datbase (https://alphafold.ebi.ac.uk) with the SwissModel Repository (https://swissmodel.expasy.org/repository).

Binary dump of the data is available at https://vsb.fbb.msu.ru/share/aozalevsky/alphafold/alphafold2_vs_swissmodel/

Dump can be loaded with dill:

```
with open('dump_20210815.dump', 'rb') as f:
    data = dill.load(f)
```
