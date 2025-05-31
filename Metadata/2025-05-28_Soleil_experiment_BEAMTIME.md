---
layout: post
title: 2025-05-28_Soleil_experiment_BEAMTIME
date: '2025-05-28'
categories: Processing
tags: Flow no flow project
---
## Soleil 2025. *Pocillopora spp.* Flow / No flow   

### ***Resume of the project***

In the island of Mo'orea located in French Polynesia, *Pocillopora spp.* are present and conciderate as dominante species around the island (back reef - fore reef) following many event as Crown of Throne, bleaching event (Gonzalo Pérez-Rosales et al. 2021). *Pocillopora spp.* show lot of plasticity depending of the depth, light and courant (Johnston et al. 2017). Identified *Pocillopora spp.* at species level are complicated only by morphology. Molecular work need to be done to detect and identified the species level using mtORF (Johnston et al. 2022). In this experiment we identify 4 differents species *P.verrucosa* (Haplotype 3), *P. meandrina* (Haplotype 1a - 8a), *P. tuahiniensis* (Haplotype 10)(new specie describe by Johnston and Burgess 2023), *P. grandis* (Haplotype 1a) sampled at 2 differents sites conditions; Haapiti **Flow site** (W 149.883782438236 - S 17.5650093638768)and Manava **No flow site** (W 149.807646130636 - S 17.4756927846393). 
Our goal it's to identified the difference and the plasticity the coral make between a site with a hight flow regime compare to a low flow regime condition. For doing that we run tomography scanning (Scucchia et al. 2023) on our samples at different BeamLine.     

### Idea   
Different growth environments induce changes at multiple levels of the skeletal hierarchy, from macro- to micro-scale in corals. Therefore, we would like to obtain morphological data of the adult coral *Pocillopora spp.* of 4 different species, to characterize the distribution of struts and other microstructures in 3D at a resolution better than 1 µm. We will examine the interplay between µm and sub-µm porosity, shape, and density gradients by collecting both low-resolution overview as well as local-region-of-interest submicron 3D X-ray tomographic data. Such data will enrich our ongoing research, which seeks to provide new insights into coral adaptation in various ocean environments.


### Objective
We will examine the interplay between µm and sub-µm porosity, shape and density gradients by collecting both low-resolution overview as well as local-region-of-interest submicron 3D X-ray tomographic data.


### History of the samples    
#### Colonies from the field   
![colonie_figure_sesesame.png](https://pierrickharnay.github.io/PierrickHarnay_Notebook/images/colonie_figure_sesesame.png) 

### **Samples preparation**
Samples previously prepared for 2024-06-03 SESAME experiment (n=2/specie/flow condition) were imaged. For the remaining coral samples (n=3), the same procedure was used to prepare small pieces of coral taken from the tip, using a wet band-saw. These nubbins, approximately 1 cm^3, were glued onto a SEM stub. 

For a subset of samples (n=1) a second piece of coral was cut, for mechanical testing. The flat top and bottom sides of these samples where sandwiched and set between acrylic (Bosworth Trim PEMA Temporary Resin Acrylic, Keystone) to create flat parallel surfaces where compressive forces could be evenly distributed. These samples were imaged, then underwent compression using a wrench, and then re-imaged. 

![images/coral_flow_sample_diagram.jpeg](*need to enter link, once website working*)

![images/Coral_set_up_soliel_2025.png](https://github.com/talimass/Talimass_Lab_Notebook_Mass_Lab/blob/d0a6d5125c525d69758046df85e371f7bd6d0c8a/images/Coral%20set%20up_soliel%202025.png)

The ANATOMIX beamline was configured to use a white beam with a high mean energy of 45 keV, achieved by using 450 µm thick Cu and 26 Au filters combined with a gap of 5.5-6.7 mm. We used 2 different camera setups: a 2x lens yielding an effective pixel resolution of 3.08 µm and a 10x camera and lens setup yielding a pixel resolution of 0.65 µm. A propagation based tomographic setup was used. To reveal internal inclusions, defects (cracks), and micropores, we explored a range of sample-detector propagation distances (dlts motor): for the low resolution, 1000, 300 and 250 mm distances (37 mm difference to motor encoder), for the high resolution, 87, 100 and 150 mm (12 mm difference to motor encoder). We first acquired images at 2x of two regions of interest - the growing tip and an older region immediately below the tip. Half acquisition scanning allowed us to capture sufficiently large cross-sectional regions of the coral. A total of 117 datasets were collected with these settings. We then switched to the high-resolution setup (after testing the 20x - 325 nm setup at lower energy but with limited feature visibility) to image each sample with the 10x setup. The ca. 100 scans of the same regions will foster multi-resolution alignment of the features in the skeletons. 

### Scan file names 
32-bit reconstructions were produced, without Paganin filtering. These reconstructions were then converted to 16-bit, clipping the data to [-7,9] for the 2x images and [-55,54] for the 10x images. Raw data and 16-bit reconstructions were transferred to hard-drives, and copies of 32-bit reconstructions remained on Soleil servers (temporary).










