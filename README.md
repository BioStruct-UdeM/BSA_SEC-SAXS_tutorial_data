# SAXS dataset for SEC-SAXS data analysis tutorial

Tutorial [here](http://airen.bcm.umontreal.ca/biostruct/SAXS_tutorials/).


## Composition of the dataset

This dataset includes processed (radially averaged and mask-corrected) SAXS data from a sample of bovine serum albumin (BSA).

Data can be found in the `scattering_data/processed` folder.

The rest of the data (averaged, subtracted, output of various analysis softwares) is saved in the described structure below.

```raw
├── README.md           <- The top-level README for developers using this project.
│
├── processed_data
│   ├── DAMMIF          <- Output of DAMMIF.
|   ├── GNOM            <- Output of GNOM.
|   └── series          <- Output of the series analysis in RAW.
|
├── scattering_data
|   ├── processed       <- Integrated SAXS data acquired.
|   ├── subtracted      <- The final, buffer-subtracted averaged scattering data for modeling.
||
└── workspaces          <- RAW workspaces.
```


## Experimental conditions

Scattering data was acquired as 60 seconds exposure frames over the course of the SEC, at a flow rate of 0.1 ml/min during the elution. The sample capillary temperature was set to 20 °C and the MAXS detector configuration was used (detector distance from sample of 600 mm).

The data was acquired on 2020-01-23 by [Normand Cyr](https://www.github.com/normcyr) at the [Structural Biology Platform](https://biochimie.umontreal.ca/plateformes-scientifiques-bmm/biologie-structurale/) of the Université de Montréal.

- Instrument: Xenocs BioXolver L
- X-rays generator: Excillum MetalJet D2+ 70 kV (λ = 1.34 Å)
- Detector: Dectris PILATUS3 R 300K
- SEC system: GE Healthcare Life Sciences ÄKTAmicro coupled to a Superdex 200 10/300 Increase column


## Additional sample information

The buffer used was 20 mM Tris pH 7.5, 150 mM NaCl.
