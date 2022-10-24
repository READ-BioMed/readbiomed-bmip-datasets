# NCBI derived data

## Pathogen data

[ncbi-pathogens-data](./ncbi-pathogens-data) 

## Prion data

[prpsc-ncbi-data](./prpsc-ncbi-data)

## Toxin data

[toxin-ncbi-data](./toxin-ncbi-data) contains a set of XML files with information collected about toxins. The files contains a list of PMIDs recovered for that toxin from MEDLINE in the `MeSHPMID` tag and the name of the toxin in the `name` tag.

The snippet below shows the example for `saxitoxin`.

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
