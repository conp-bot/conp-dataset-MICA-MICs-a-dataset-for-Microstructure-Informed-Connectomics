# MICA-MICs: a dataset for Microstructure-Informed Connectomics

Crawled from [OSF](https://osf.io/j532r/)

## Description

The MICA-MICs dataset provides raw and fully processed multimodal neuroimaging data acquired in 50 healthy control participants at a field strength of 3T. Modalities include high-resolution anatomical (T1-weighted), microstructurally-sensitive (quantitative T1), diffusion-weighted and resting-state functional imaging. In addition, MICA-MICs provides ready-to-use connectomes built across multiple parcellation schemes based on brain anatomy, function, and histology (18 parcellations in total). Processed matrices are available for each imaging modality across a range of parcellation scales. Due to storage limitations, only derivatives (MRIQC outputs, processed matrices, and gradients) are made available in this repository. Researchers wishing to access MICA-MICs raw data can do so from the Canadian Open Neuroscience Platform's data portal: https://portal.conp.ca/dataset?id=projects/mica-mics 

Please cite the following reference if you use this dataset:
Royer, J., Rodriguez-Cruces, R., Tavakol, S., Lariviere, S., Herholz, P., Li, Q., Vos de Wael, R., Paquola, C., Benkarim, O., Park, B., Lowe, A.J., Margulies, D.S., Smallwood, J., Bernasconi, A., Bernasconi, N., Frauscher, B., Bernhardt, B.C., 2021. An open MRI dataset for multiscale neuroscience. bioRxiv 2021.08.04.454795. https://doi.org/10.1101/2021.08.04.454795

## DOI: 10.17605/OSF.IO/J532R

## WIKI

The human brain is a highly interconnected network which can be described at multiple spatial and temporal scales. Neuroimaging, in particular magnetic resonance imaging (MRI), has provided a window into brain structure and function, offering versatile contrasts to assess its multiscale organization. Here, we leverage the rich descriptions of brain structure and function offered by MRI to further our understanding of human brain organization across modalities and spatial scales. MICA-MICs is a dataset for microstructure-informed connectomics providing raw and fully processed multimodal neuroimaging data acquired in 50 healthy control participants at an MRI field strength of 3T. Modalities include high-resolution anatomical (T1-weighted), microstructurally-sensitive (quantitative T1), diffusion-weighted, and resting-state functional imaging. We additionally provide users with ready-to-use connectomes built across multiple parcellation schemes based on histology (e.g. Von Economo), sulco-gyral landmarks (e.g. Desikan-Killiany), and function (e.g. Schaefer atlases), for a total of 18 different parcellations of varying spatial scale. All connectome matrices were generated using micapipe (https://micapipe.readthedocs.io/), a robust pre-processing pipeline for multimodal neuroimaging data. By granting access to data modalities at different pre-processing stages, this dataset will streamline the development of novel approaches to study complex interactions between regional and networks-level properties of the human brain.

Only derivatives data are made available on this OSF repository. However, all raw data can be easily accessed from the Canadian Open Neuroscience Platform's data portal: https://portal.conp.ca/dataset?id=projects/mica-mics

The derivatives directory for MICA-MICs includes three subdirectories:
- gradients: In this subfolder, *gradients.zip* includes gradients computed from all data modalities and parcellated data matrices from this release.
- micapipe: All raw data from this dataset was processed using [micapipe][1]. Matrices obtained from this processing pipeline are included in *micapipe.zip* for all modalities and parcellations.
- mriqc: Image quality metrics and detialed reports are made available for raw T1-weighted and resting-state functional scans in *mriqc.zip*.

-----

**Please cite the following reference if you use this dataset:**

Royer, J., Rodriguez-Cruces, R., Tavakol, S., Lariviere, S., Herholz, P., Li, Q., Vos de Wael, R., Paquola, C., Benkarim, O., Park, B., Lowe, A.J., Margulies, D.S., Smallwood, J., Bernasconi, A., Bernasconi, N., Frauscher, B., Bernhardt, B.C., 2021. An open MRI dataset for multiscale neuroscience. bioRxiv 2021.08.04.454795. https://doi.org/10.1101/2021.08.04.454795


  [1]: https://micapipe.readthedocs.io/