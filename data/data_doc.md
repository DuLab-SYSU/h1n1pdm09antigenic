This dataset was compiled from historical influenza surveillance and vaccine strain evaluation reports published by the Worldwide Influenza Centre (WIC) at the Francis Crick Institute. WIC also serves as a World Health Organization (WHO) Collaborating Centre for Reference and Research on Influenza. Its reports are primarily used to support the evaluation and recommendation of seasonal influenza vaccine strain composition by WHO.

This dataset retains only data related to A(H1N1)pdm09, with a particular focus on antigenic characterisation results for H1N1 viruses reported by WIC. The original information was mainly extracted from tables reporting results from Hemagglutination Inhibition (HI) assays.

The data are stored by report year. The overall directory structure is:

```text
data/
├── wic2010/
├── wic2011/
├── wic2012/
├── ...
├── wic2020/
├── wic2021/
└── wic2022/
```

Each Excel file within a yearly folder corresponds to an H1N1 antigenic assay table from the original WIC PDF report or to a subsection of a table that was split during data extraction.
