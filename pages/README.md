## About

This dataset accompanies the didactic Luna walkthrough (https://zzz.bwh.harvard.edu/luna-walkthrough/), which is designed to introduce the open-source [Luna](https://zzz.bwh.harvard.edu/luna/) software package for sleep signal analysis, with a focus on sleep EEG micro-architecture.  The data are whole-night hd-EEG recordings from a subset (N=20) of the healthy control individuals from the GRINS (Global Research Initiative on the Neurophysiology of Schizophrenia) project (PMIDs: [35578829](https://pubmed.ncbi.nlm.nih.gov/35578829/), [39297495](https://pubmed.ncbi.nlm.nih.gov/39297495/), [38858652](https://pubmed.ncbi.nlm.nih.gov/38858652/)).

The goal of the walkthrough is to demonstrate relatively "real-world" typical usage of Luna to validate, manipulate, clean and then analyze a dataset. Importantly, a number of manipulations to the original ([**v1**](:files_path:/v1)) data have been  explicitly introduced, to make them harder to work with: the [**v2**](:files_path:/v2) data (the starting point for the walkthrough) contains corrupt signals, truncated or misaligned staging, and altered labels/formats, etc. The walkthrough shows how Luna can detect and potentially correct some of these issues, before stepping through various areas of sleep EEG analysis.

## Data de-identification

All personally identifiable information (PII) has been removed from the data files by the NSRR team.

## Data overview

See [this walkthrough page](https://zzz.bwh.harvard.edu/luna-walkthrough/data/) for full details.  

[**v1**](:files_path:/v1)

The "original" sleep EEG studies, with physiological data in EDF and annotations in Luna  [.annot](https://zzz.bwh.harvard.edu/luna/ref/annotations/#annot-files).  Note that these data are denoted as the _"original"_ only for the purpose of this didactic walkthrough:  the larger set of recordings previously reported (e.g. PMIDs:  [35578829](https://pubmed.ncbi.nlm.nih.gov/35578829/), [39297495](https://pubmed.ncbi.nlm.nih.gov/39297495/), [38858652](https://pubmed.ncbi.nlm.nih.gov/38858652/)) were sampled at a higher sample rate (500 Hz) and with EOG/EMG signals, etc. 

[**v2**](:files_path:/v2)

From the original (`v1`) data, a second manipulated version (`v2`) was created, purposefully introducing variations in standards and conventions as well as several flavors of data corruption, as described [here](https://zzz.bwh.harvard.edu/luna-walkthrough/data/#manipulated-data-v2).  The EEG data are still in EDFs (for the same N=20 individuals); the annotation data have been reformatted to reflect a diverse set of formats.

[**/aux**](:files_path:/aux)

Auxiliary data files used in the walkthrough, including basic demographic information (age, sex as a tab-delimited text file), mapping files for channels and annotations, channel location maps, and subfolders with age-prediction model files and POPS model files.  See [here](https://zzz.bwh.harvard.edu/luna-walkthrough/prep/#data) for more details.

## Access and usage restrictions

The Luna/GRINS dataset is only available for non-commercial use.

## Citation and acknowledgement

When using these data, users must cite the following:

 - Luna walkthrough URL : https://zzz.bwh.harvard.edu/luna-walkthrough/

 - NSRR URL : https://sleepdata.org/datasets/luna-grins/

 - NSRR : [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)

 - GRINS : 

     - [Wang J, Jiang C, Guo Z, Chapman S, Kozhemiako N, Mylonas D, Su
       Y, Zhou L, Shen L; GRINS Consortium; Qin S, Murphy M, Tan S,
       Manoach DS, Stickgold R, Huang H, Zhou Z, Purcell SM, Hall M,
       Hyman SE, Pan JQ. Study Protocol: Global Research Initiative
       on the Neurophysiology of Schizophrenia (GRINS) project. BMC
       Psychiatry. 2024 Jun 10;24(1):433. doi:
       10.1186/s12888-024-05882-1. PMID: 38858652; PMCID:
       PMC11165775.](https://pubmed.ncbi.nlm.nih.gov/38858652/)

     - [Kozhemiako N, Jiang C, Sun Y, Guo Z, Chapman S, Gai G, Wang Z,
       Zhou L, Li S, Law RG, Wang LA, Mylonas D, Shen L, Murphy M, Qin
       S, Zhu W, Zhou Z, Stickgold R, Huang H, Tan S, Manoach DS, Wang
       J, Hall MH, Pan JQ, Purcell SM. A spectrum of altered non-rapid
       eye movement sleep in schizophrenia. Sleep. 2025 Feb
       10;48(2):zsae218. doi: 10.1093/sleep/zsae218. PMID: 39297495;
       PMCID: PMC11807884.](https://pubmed.ncbi.nlm.nih.gov/39297495/)

Users must include the following text in any Acknowledgements:

> Data collection was supported by a grant (RO1 HS12032) from the Agency for Healthcare Research and Quality (AHRQ) and a grant (RO1 OH07567) from the National Institute for Occupational Safety and Health.  The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*March 2025*

- Initial deposition of the Luna/GRINS walkthrough data

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
