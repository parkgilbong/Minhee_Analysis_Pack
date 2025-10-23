# Minhee Analysis Package

**An integrated software package for detection and management of spontaneous synaptic events**

[![DOI](https://img.shields.io/badge/DOI-10.1186%2Fs13041--021--00847--x-blue)](https://doi.org/10.1186/s13041-021-00847-x)

Last update: 2022-07-25
## Introduction

To understand the information encoded in connections between neurons, postsynaptic current (PSC) has been widely measured as a primary index of synaptic strength in neurophysiology. Neurons communicate with each other in a precisely timed manner within a complex neural network, releasing and receiving neurotransmitters in synapses through synaptic transmission. PSCs are generated spontaneously or evoked by presynaptic spikes, represented as miniature or spontaneous responses in postsynaptic neurons. Quantitative analysis of these synaptic events is fundamental to characterizing synaptic properties in the brain.

While the results of quantitative analysis of PSCs are informative, the workflow is time-consuming and laborious. Although several automated methods have been developed for detecting spontaneous PSCs, repetitive steps such as quantification, management, and statistical analysis still require considerable effort. An integrated solution is needed to simplify the workflow from detection to interpretation of PSC data.

**Minhee Analysis Package** is an integrated standalone software package capable of detecting, sorting, and quantifying PSC data. This package is built not just to detect spontaneous PSCs, but also to search and visualize them in a custom way, and perform hypothesis testing on the retrieved data.

### Key Features

- **Stepwise exploratory algorithm** for precise PSC detection
- **Customizable data retrieval** in user-defined manner
- **Automatic visualization** with general and cumulative histograms
- **Statistical hypothesis testing** including:
  - Kolmogorov-Smirnov (K-S) test for comparing distributions between groups
  - Independent two-sample t-test for comparing averaged values between groups
  - One-way ANOVA for multiple group comparisons
- **Easy-to-use graphical user interface (GUI)**
- **Exponential curve fitting** (optional, toggle with Ctrl+3/Ctrl+4)
- **Data export capabilities** for further analysis

The detection algorithm has been validated using both simulated and experimental data. All features are accessible via an intuitive GUI, improving the convenience and efficiency of neurophysiologists by simplifying the workflow from detection to quantification.

## Citation

If you use Minhee Analysis Package in your research, please cite:

> Kim, Y.G., Shin, J.J., Kim, S.J. (2021). Minhee Analysis Package: an integrated software package for detection and management of spontaneous synaptic events. *Molecular Brain*, 14, 138. https://doi.org/10.1186/s13041-021-00847-x

 ## Package release and update log
* Release 1.1.3 from July 25, 2022
   #### Notes
      -	From this version, users can turn on/off the Exponential curve fitting. To toggle it, users may either access the runtime menu (View>Event Trace>Exponential curve fitting>ON or OFF), or may use a hot key. Ctrl+3 and Ctrl+4 are shortcuts to turn the function on and off, respectively. 
      -	When the program finishes importing a data file, the file name with the extension appears in its window title.
      -	The exact p-value is provided as a result of the K-S test.
      -	Bug fixed and GUI has been improved. 

* Release 1.1.2 from May 23, 2022
   #### Notes
      -	Bug fixed and GUI has been improved. 

* Release 1.1.1 from Aug 9, 2021
   #### Notes
      -	The methodology article has been published in Molecular Brain doi: 10.1186/s13041-021-00847-x
      -	The Comparison, Export, Save functions from the previous version have been renamed Hypothesis testing, Export Cumulative Plot, and Save Summary Table, respectively. 
      -	A new function called ‘Save Whole Data’ has been added to the Minhee Retriever, which allows the users to save all retrieved events to a file in text format. 
      -	One-way ANOVA was added to the Hypothesis testing function in the Minhee Retriever. 
      -	GUI of the Minhee Retriever has been changed.
      -	After performing the Hypothesis testing, the Minhee Retriever displays detailed statistical information.    

* Release 1.0.1 from May 29, 2021
   #### Notes
      -	Bug fixed. 
      -	A resource preprint that describes the algorithm, all features and examples has been released. 
       (https://www.biorxiv.org/content/10.1101/2021.05.27.443730v1.full)

* Initial (1.0.0) Release from Wednesday, November 18, 2020
   #### Notes
      -	It is the first release of the package. 
      -	The initial version of Minhee analysis and Minhee retriever is 1.0.0.
      -	A description of all features and examples of use can be found at https://github.com/parkgilbong/Minhee_Analysis_Pack 
 
![Figure 1. System overview](https://media.springernature.com/full/springer-static/image/art%3A10.1186%2Fs13041-021-00847-x/MediaObjects/13041_2021_847_Fig1_HTML.png?as=webp)
  
 ## Installation (Do only once)  
  1. Download all files from the Volume folder in (github.com/parkgilbong/Minhee_Analysis_Pack)
  2. Run setup.exe 
  3. General windows for installing the program will appear.
  4. Executable file will be in NeuroPhysiology Lab folder.    
 
  ## **Minhee Analysis**
  ![Figure 2. GUI of Minhee Analysis](https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs13041-021-00847-x/MediaObjects/13041_2021_847_Fig6_HTML.png?as=webp)  
*****
 ## **Minhee Retriever**
  ![Figure 3. GUI of Minhee Retriever](https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs13041-021-00847-x/MediaObjects/13041_2021_847_Fig7_HTML.png?as=webp)
