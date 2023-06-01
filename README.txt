This code is licenced under Creative Commons designation CC BY-SA.

This is the README for SARS-CoV-2 infection model published in the following paper:


Hemalatha Sasidharakurup, Geetha Kumar, Bipin Nair and Shyam Diwakar, Mathematical Modeling of Severe Acute Respiratory Syndrome Coronavirus 2 Infection Network with Cytokine Storm, Oxidative Stress, Thrombosis, Insulin Resistance, and Nitric Oxide Pathways, 
OMICS Journal of Integrative Biology. 2021 Dec;25(12):770-781. doi: 10.1089/omi.2021.0155. Epub 2021 Nov 22.  Accessible at https://pubmed.ncbi.nlm.nih.gov/34807729/

The biochemical reactions involved in the SARS-CoV-2 infection related cytokine storm, immune response, insulin, thrombosis and NO pathways were modeled to understand crosstalk, interdependency and biological feedback loops, in order to find crucial biomarkers that could contribute to emergent properties of the underlying biological networks. With this model, excessive immune response, inflammatory cytokines and chemokines may be considered as the key players of COVID-19 infection progression. 

Pathways were modeled and simulated using the biochemical pathway visualization program CellDesigner (www.celldesigner.org), a modeling tool for gene-regulatory and biochemical networks that support graphical notation and listing of symbols (Funahashi et al., 2003). 

Last updated 10-October-2021
Developed by : Hemalatha Sasidharakurup & Shyam Diwakar    
Amrita Mind Brain Center, Amrita Vishwa Vidyapeetham, India.
Email: shyam@amrita.edu, hemalathas@am.amrita.edu
https://amrita.edu/mindbrain/

Requirements
============

Windows machine with CellDesigner 4.4.2 and java installed.

Tested with the following 
=========================
Windows 10 desktop, 64 bit.
CellDesigner version 4.4.2
Java version 1.8.0_261
SBMLsqueezer version 2.1


CellDesigner environment setup
==============================

1. Download and install CellDesigner4.4.2 (http://www.celldesigner.org/) , if not already installed. 

2. Download and install Java 1.8 , if not already installed. 

3. Locate CellDesigner installed folder in the computer. (Default path will be  “C:\Program Files\CellDesigner4.4.2”).

4. Download and copy the file “SBMLsqueezer_v2.0.1_incl-libs” (7250KB) in the plugin folder, from the link: 
http://www.cogsys.cs.uni-tuebingen.de/software/SBMLsqueezer/downloads/SBMLsqueezer_v2.1.jar

5. Rename the old file name as “SBML-squeezer…_back” or something similar so that old file will have a different name from the new file.

6. Download “jsbml-1.1-a1-incl-libs.jar” from the following link and rename the downloaded file to “jsbml-1.0-incl-libs.jar”

Link: http:// www.cogsys.cs.uni-tuebingen.de/software/SBMLsqueezer/downloads/jsbml-1. 1-a1-incl-libs.jar 

7. Copy the renamed file “jsbml-1.0-incl-libs.jar” into the lib folder. 

8. Restart the CellDesigner. 

If it doesn't work, download CellDesigner 4.4 Google Summer of Code edition, celldesigner.jar from the following link and replace it with the default celldesigner.jar which is located in the CellDesigner installed folder. 
Link: http://www.celldesigner.org/~funa/GSoC/celldesigner.jar

How to reproduce the model
==========================

1. Download the given code and save the file in a folder.

2. Load the file in CellDesigner.

3. Set the initial values for each species as given in the paper.

4. Go to toolbar menu. Select Plugin, from the dropdown list, select SBML squeezer 2.0.1 and squeeze kinetic laws. 
   Users can also right click on each reactions and "Edit kineticLaw" to apply kinetic laws manually.

5. Go to Simulations tab, select ControlPanel and click "execute" button to run the simulation.   
   A graph will be produced for each pathway.

6. One may have to rearrange the species in CellDesigner by dragging it manually to have the look and feel of the pathway.

7. Users can also use interactive simulations to adjust the values in an intuitive manner and observe the changes. 

