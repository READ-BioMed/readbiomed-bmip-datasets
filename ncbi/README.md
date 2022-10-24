# NCBI derived data

## Pathogen data

[ncbi-pathogens-data](./ncbi-pathogens-data) 

## Prion data

[prpsc-ncbi-data](./prpsc-ncbi-data) contains a set of XML files with information collected about PrPSc prions. The files contains a list of PMIDs recovered for that prion from MEDLINE in the `MeSHPMID` tag, the PubMed Query used to recover the PIMDs in `pubMedQuery` and the species in the `species` tag. It contains as well a [terms.txt](./prpsc-ncbi-data/terms.txt) file with the list of prions.

The snippet below shows the example for [cat PrPSc](./prpsc-ncbi-data/Sc (cat).xml).

```
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<PrPSc>
    <MeSHPMID>19622059</MeSHPMID>
    <MeSHPMID>19335885</MeSHPMID>
    <MeSHPMID>15763182</MeSHPMID>
...
    <pubMedQuery>"PrPSc Proteins"[MH] AND "cats"[MH]</pubMedQuery>
    <species>cat</species>
</PrPSc>
```

## Toxin data

[toxin-ncbi-data](./toxin-ncbi-data) contains a set of XML files with information collected about toxins. The files contains a list of PMIDs recovered for that toxin from MEDLINE in the `MeSHPMID` tag and the name of the toxin in the `name` tag. It contains a list of toxins in the [terms.txt](./toxin-ncbi-data/terms.txt) file.

The snippet below shows the example for [saxitoxin](./toxin-ncbi-data/saxitoxin.xml).

```
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<toxin>
    <MeSHPMID>33916687</MeSHPMID>
    <MeSHPMID>33526188</MeSHPMID>
    <MeSHPMID>33526182</MeSHPMID>
...
    <name>Saxitoxin</name>
</toxin>
```
