# Organoid-analysis
README file
===========

This repository contains code developed by the Gulf Coast Consortia Combinatorial Drug Discovery Program (CDDP) at Texas A&M Center – Institute of Bioscience and Technology at the Texas Medical Center in Houston, Texas.

The code is experimental and not thoroughly tested across all machines. If you get an error, or something doesn't seem to be working, PLEASE LET US KNOW. Most of the code here is written in Python and Pipeline Pilot, although there are some R scripts that are automated using Pipeline Pilot (Biovia).

Contact:
Reid T. Powell
repowell@tamu.edu


CONTENTS
========
README         This file.
LICENSE        How this code is licensed.
USAGE		Instructions to replicate the finds of the study
Images/		Example images files/folder structure. This is for demonstration purposes, likewise, does not contain all images. 
Code/           Jupyter notebooks and Pipeline Pilot scripts.
Metadata/	Experimental metadata

System requirements:
This code was not thoroughly tested on a wide range of machines. The system configuration that was used to perform all analysis/benchmarking was performed on a Dell PowerEdge R740xd server running Windows Server 2016 standard edition and equipped with: dual 3.3 Ghz Xeon Gold 6246 CPUs [Intel], 192 Gb DDR5 RAM, and a NVIDIA Tesla V100 32Gb purchased from Dell EMC using funds from the CPRIT CFSA RP150578. 
All scripts have been tested on a machine running Windows 2016 and Windows 10, no other operating systems have been tested. DNN feature embeddings have been optimized to run on a PC equipped with a GPU, however, this is not required.
•	Python 3.8 and libraries, Python 2.7 not supported
o	Required python libraries:
	Pythorch - https://pytorch.org/. Download and manipulate neural networks
	Numpy – https://www.numpy.org. Used for image manipulation
o	Optional python libraries
	PyQT5 - https://pypi.org/project/PyQt5/5.10/. Interactive file browsing
•	R 3.4+
o	Required R Libraries
	Caret - https://topepo.github.io/caret/. kNN functions
	e1071 - https://cran.r-project.org/web/packages/e1071/index.html. SVM functions
•	Pipeline Pilot 2018 Server
o	Scripts developed using Pipeline Pilot require a paid license that may be purchased from: https://www.3ds.com/products-services/biovia/products/data-science/pipeline-pilot/. Installation instructions are provided with purchase. Must configure R and ImageJ integration
