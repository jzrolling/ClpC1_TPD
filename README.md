
[bioRxiv]: https://www.biorxiv.org/content/10.1101/2023.02.14.528552v1

# ClpC1_TPD
### Code deposit for our recent manuscript:
### [Chemically-induced targeted protein degradation in mycobacteria uncovers antibacterial effects and potentiates antibiotic efficacy][bioRxiv]
*Proteolysis-targeting chimeras (PROTACs) represent a new therapeutic modality involving selectively directing disease-causing proteins for degradation through proteolytic systems. Our ability to exploit this targeted protein degradation (TPD) approach for antibiotic development remains nascent due to our limited understanding of which bacterial proteins will be labile TPD targets. Here, we use a genetic system to model chemically-induced proximity and degradation to screen essential proteins in Mycobacterium smegmatis (Msm), a model for the major human pathogen M. tuberculosis (Mtb). We find that drug-induced proximity to the bacterial ClpC1P1P2 proteolytic complex is sufficient to degrade many, but not all, endogenous Msm proteins, profoundly inhibiting bacterial growth for some targets. We also show that TPD can potentiate the effects of existing antibiotics targeting the same pathways and complexes. Together, our results identify specific endogenous mycobacterial proteins as attractive targets for future Mtb PROTAC development, as both standalone antibiotics and potentiators of existing antibiotic efficacy.*

[flow]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks/flow_analysis
[plate]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks/plate_image_analysis
[rpoA]:https://github.com/jzrolling/ClpC1_TPD/tree/main/ClpC1_TPD_jupyter_notebooks/microscopy_analysis

### Jupyter notebooks that were used to perform image analysis and render plots are provided as follows:
* **[Notebooks for processing flow cytometry data.][flow]**
* **[Notebooks for processing rpoA timelapse data.][rpoA]**
* **[Notebooks for processing plate photos.][plate]**


### Note that majority of the image analysis was performed using momia2, which was designed to perform miscellaneous mycobacterial imaging data.
momia2 is currently under development (albeit slowly), you may install the momia2 development version by running:
```
pip install git+https://github.com/jzrolling/momia2-dev.git
```




