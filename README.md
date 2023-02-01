# Pathogens data set

This data set has been generated for the annotation of pathogens from the scientific literature using the [readbiomed-ncbi-pathogen-dataset-generation](https://github.com/READ-BioMed/readbiomed-ncbi-pathogen-dataset-generation)
package.

## NCBI taxonomy pathogen data set (ncbi folder)

National Center for Biotechnology Information (NCBI) data sources have been used to automatically collect information about pathogens from NCBI database resources. The folder [ncbi](./ncbi) has the files for [taxonomic pathogens](./ncbi/ncbi-pathogens-data), [PrPSc prions](./ncbi/prpsc-ncbi-data) and [toxins](./ncbi/toxin-ncbi-data) and a description of the content of each folder.

The information for each pathogen is in XML format and includes meta-data about the pathogen, information about subspecies and PubMed and PubMed Central identifiers that can be used to recover information about these pathogens from the scientific literature.

## Manually annotated data set (manual-set folder)

The manual-set folder contains manual annotation for the characterisation of actively research pathogens from the scientific literature.

More information about the manually annotated data set is available [here](./manual-set).

# References

If you use this work in your research, remember to cite it. The publication below contains additional information about the creation of this data set.

```
@article{jimeno2023classifying,
  title={Classifying literature mentions of biological pathogens as experimentally studied using natural language processing},
  author={Jimeno Yepes, Antonio and Verspoor, Karin},
  journal={Journal of Biomedical Semantics},
  year={2023},
  volume={14},
  number={1},
  doi={10.1186/s13326-023-00282-y},
  url={https://doi.org/10.1186/s13326-023-00282-y}
}
```
