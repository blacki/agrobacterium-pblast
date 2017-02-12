# spicy-tomato

Agrobacterium genome database that has blast tool 

BLAST against Agrobacterium tumefaciens genome, [protein](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch&PROG_DEFAULTS=on&PROG_DEF=blastp&BLAST_SPEC=MicrobialGenomes_1435057&DB_GROUP=AllMG)

Then we can do a protein blast against each amino acid sequence

We are looking for proteins with the following tags:

```
GERLRVT
GERLRFT
GERMRVT
GERMRFT
GDRLRVT
GDRLRFT
GDRMRVT
GDRMRFT
```


# Alternate Approach

every possible reverse translation of those motifs + reverse complement 

Identify every place that there is a match for the corresponding DNA + stop codon 

