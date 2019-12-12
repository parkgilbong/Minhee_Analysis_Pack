# Minhee_Analysis_Package 2019-11-05
 ## Introduction  
  Neurons communicate with each other in a precisely timed manner within a complex neural network. In order to understand how this communication carries information in the brain, it is essential to investigate characteristics of synaptic transmission between neurons. Of several observations representing the characteristics of synaptic transmission between neurons, the postsynaptic current (PSC) has been broadly utilized1–3. In terms of neurophysiology, PSCs are generated spontaneously or following presynaptic spikes, reflecting the nature of the synaptic transmission between neurons itself (ref). Hence, quantitative analysis of spontaneous PSCs in neurons is a fundamental step for the characterization of synapses in the brain.   
 While the results of quantitative analysis of PSCs are informative, a workflow for this analysis is time-consuming and laborious. To simplify the workflow and make it more efficient, several automated methods have been implemented in the detection of spontaneous PSCs4–9. After the completion of successful detection of PSCs, it still remains consecutive and iterative steps to interpret the results. These steps include averaging and visualizing the data grouped by a custom manner, and performing statistical assessments that neurophysiologists uses typically. Although there have been several attempts to improve the efficiency of the event detection process for electrophysiologists, however, there is still a lack of solutions to efficiently manage the analyzed data thereafter10. An integrated solution would improve the convenience and efficiency of researcher’s activity by simplifying the workflow from detection to interpretation of PSC data.     
 Here, we present an integrated software package for detection and management of spontaneous synaptic events. This package, Minhee Analysis Package, is built to detect spontaneous PSCs, search and visualize them in a custom way, and perform the hypothesis testing of the retrieved data. This package utilizes a stepwise and exploratory search algorithm to detect PSCs. To create up-to-date tables of data, users can search their data in the way that users define. After the successful retrieval of the data, the package automatically generate general and cumulative histograms to represent the distribution of data. The package serves two hypothesis testings, student’s t-test for comparing averaged values between two groups and Kolmogorov-Smirnov (K-S) test for comparing distribution of data between two groups. All of Minhee Analysis Package’s functionality is accessible via its easy-to-use graphical user interface (GUI). Minhee Analysis Package can be downloaded at http://www.github.com/parkgilbong/Minhee_Analysis_Pack.   
  
![Figure 1. System overview](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Minhee%20Analysis/System%20overview.PNG) 
  
 ## Installation (Do only once)  
  1. Download all files from the Volume folder in (github.com/pargilbong/Minhee_Analsys_Pack)
  2. Run setup.exe 
  3. General windows for istalling the program will appear.
  4. Executable file will be in NeuroPhysiology Lab folder.    
 *****
  ## **Minhee Analysis**
 ![Figure 2. GUI of Minhee Analysis](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Minhee%20Analysis/Screenshot%20of%20Minhee%20Analysis.png)  
![1.Set parameters](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Analysis_step_1.PNG)
![2.Import file](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Analysis_step_2.PNG)
![3.Browse data](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Analysis_step_3.PNG)
![4.Edit event](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Analysis_step_4.PNG)
![5.Select event](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Analysis_step_5.PNG)
![6.Save unit file](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Analysis_step_6.PNG)
*****
 ## **Minhee Retriever**
![Figure 3. GUI of Minhee Retriever](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Minhee%20Retriever/Screenshot%20of%20Minhee%20Retriever.png)
![1.Retrieval of unit files](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Retriever_step_1.PNG)
![2.Display retrieved data](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Retriever_step_2.PNG)
![3.Comparison analysis](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Retriever_step_3.PNG)
![4.Export plot data & Save result](https://github.com/parkgilbong/Minhee_Analysis_Pack/blob/master/Use%20Example/Minhee_Retriever_step_4.PNG)
