# NCBI derived data

Pathogen information is divided into taxonimic pathogens, PrPSc prions and toxin data detailed in the following sections.

## Taxonomic pathogen data

[ncbi-pathogens-data](./ncbi-pathogens-data) contains a set of XML files with information about taxonomic pathogens. The files contain several lists of PubMed Identifiers (PMIDs).

The snippet below shows the example for [Escherichia coli](ncbi-pathogens-data/Escherichia coli.xml).

```
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<pathogen>
    <subSpecies>
        <id>2822132</id>
        <scientificName>Escherichia coli O128ac:H12</scientificName>
    </subSpecies>
...
    <PMCID>8185355</PMCID>
    <PMCID>8185337</PMCID>
    <PMCID>8185306</PMCID>
...
    <GenBankPMID>26579110</GenBankPMID>
    <GenBankPMID>23190765</GenBankPMID>
    <GenBankPMID>1977705</GenBankPMID>
...
    <MeSHPMID>34404473</MeSHPMID>
    <MeSHPMID>34397035</MeSHPMID>
    <MeSHPMID>34395312</MeSHPMID>
...
    <id>562</id>
    <meSHTree>B03.440.450.425.325.300, B03.660.250.150.180.100</meSHTree>
    <otherNames>&lt;OtherNames&gt;
 &lt;Synonym&gt;
  Bacillus coli
 &lt;/Synonym&gt;
...
    <scientificName>Escherichia coli</scientificName>
</pathogen>
```

## PrPSc prion data

[prpsc-ncbi-data](./prpsc-ncbi-data) contains a set of XML files with information collected about PrPSc prions. The files contain a list of PMIDs recovered for that prion from MEDLINE in the `MeSHPMID` tag, the PubMed Query used to recover the PIMDs in `pubMedQuery` and the species in the `species` tag. It contains as well a [terms.txt](./prpsc-ncbi-data/terms.txt) file with the list of prions.

The snippet below shows the example for <a href="./prpsc-ncbi-data/Sc (cat).xml">cat PrPSc</a>.

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

[toxin-ncbi-data](./toxin-ncbi-data) contains a set of XML files with information collected about toxins. The files contain a list of PMIDs recovered for that toxin from MEDLINE in the `MeSHPMID` tag and the name of the toxin in the `name` tag. It contains a list of toxins in the [terms.txt](./toxin-ncbi-data/terms.txt) file.

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
