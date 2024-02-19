
[bioRxiv]: https://www.biorxiv.org/content/10.1101/2023.02.14.528552v1

# ClpC1_TPD
### Code deposit for our recent manuscript:
### [Chemically-induced targeted protein degradation in mycobacteria uncovers antibacterial effects and potentiates antibiotic efficacy][bioRxiv]
*Proteolysis-targeting chimeras (PROTACs) represent a new therapeutic modality involving selectively directing disease-causing proteins for degradation through proteolytic systems. Our ability to exploit targeted protein degradation (TPD) for antibiotic development remains nascent due to our limited understanding of which bacterial proteins are amenable to a TPD strategy. Here, we use a genetic system to model chemically-induced proximity and degradation to screen essential proteins in Mycobacterium smegmatis (Msm), a model for the human pathogen M. tuberculosis (Mtb). By integrating experimental screening of 72 protein candidates and machine learning, we find that drug-induced proximity to the bacterial ClpC1P1P2 proteolytic complex leads to the degradation of many endogenous proteins, especially those with disordered termini. Additionally, TPD of essential Msm proteins inhibits bacterial growth and potentiates the effects of existing antimicrobial compounds. Together, our results provide biological principles to select and evaluate attractive targets for future Mtb PROTAC development, as both standalone antibiotics and potentiators of existing antibiotic efficacy.*

[flow]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks/flow_analysis
[plate]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks/plate_image_analysis
[rpoA]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks/microscopy_analysis
[revision1]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks_revision1

### Jupyter notebooks that were used to perform image analysis and render plots are provided as follows:
* **[Notebooks for processing flow cytometry data.][flow]** (deprecated in revision1)
* **[Notebooks for processing rpoA timelapse data.][rpoA]**
* **[Notebooks for processing plate photos.][plate]** (deprecated in revision1)
* **[Notebooks generated for revision 1][revision1]** 

[plate_unet]:https://drive.google.com/drive/folders/1ngNdMPka_KaukyDj62vECfXcP6xt6zZP?usp=sharing
[microscopy_unet]:https://drive.google.com/drive/folders/1d7Otbzh51iaa62gbwXpPfXGkx0ULqhVF?usp=sharing
[microscopy_unet_new]: https://drive.google.com/drive/folders/18n4wioiCQcQfKx2iba4jwxInXc6wNgni?usp=sharing

### Pretrained UNet models for microscopy/plate image segmentation can be downloaded from:
* **[Plate photo segmentation model.][plate_unet]**
* **[Microscopy segmentation model][microscopy_unet]**
* * **[Microscopy segmentation model used for revision1][microscopy_unet_new]**

### Note that majority of the image analysis was performed using momia2, which was designed to perform miscellaneous mycobacterial imaging data analysis.
momia2 is currently under development (albeit slowly), you may install the momia2 development version by running:
```
pip install git+https://github.com/jzrolling/CleanSpace.git
```






