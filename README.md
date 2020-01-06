# Minhee_Analysis_Package last update: 2019-12-12
 ## Introduction  
  Neurons communicate with each other in a precisely timed manner within a complex neural network. To transfer information in real-time dialogues between neurons, they release neurotransmitters and also receive them in synapses, which is represented as synaptic transmission. In order to decode information in this neuronal synaptic connection, it is essential to detect, measure, and analyze characteristics of synaptic transmission between neurons. Of various elements of synaptic transmission, the postsynaptic current (PSC) has been extensively analyzed to understand neuronal synapse property in electrophysiology.1–3. In terms of neurophysiology, PSCs are generated spontaneously or evoked by following presynaptic spikes, which is represented as miniature or spontaneous responses in postsynaptic neurons respectively. These miniature and spontaneous responses can be used for quantum analysis in synaptic transmission. Therefore, quantitative analysis of synaptic events of PSCs in neurons is a fundamental step to characterize synaptic properties in the brain.       
 While the results of quantitative analysis of PSCs are informative, a workflow for this analysis is time-consuming and laborious. To simplify the workflow and make it more efficient, several automated methods have been applied in the detection of spontaneous PSCs4–9. However, even after the completion in reliable detection of PSCs, it still remains redundant following steps dragging researchers to keep doing consecutive and iterative analysis to interpret the results. These steps include averaging and visualizing the data grouped by a custom manner, and also performing statistical assessments that neurophysiologists uses typically. Although there have been several attempts to improve the efficiency of the event detection process for electrophysiologists, however, there is still a lack of solutions to efficiently manage the analyzed data thereafter10. An integrated solution would improve the convenience and efficiency of researcher’s activity by simplifying the workflow from detection to interpretation of PSC data.         
 Here, we present an integrated software package for detection and measurement of spontaneous synaptic events. This package, Minhee Analysis Package, is built to detect spontaneous PSCs, search and visualize them in a custom way, and perform the hypothesis testing of the retrieved data. This package utilizes a stepwise and exploratory search algorithm to detect PSCs. To create up-to-date tables of data, users can search their data in one’s defined manner. After the successful retrieval of the data, the package automatically generates general and cumulative histograms to represent the distribution of data. The package serves two hypothesis testing methods, student’s t-test for comparing averaged values between two groups and Kolmogorov-Smirnov (K-S) test for comparing distribution of data between two groups. All of Minhee Analysis Package’s functionality is accessible via its easy-to-use graphical user interface (GUI). Minhee Analysis Package can be downloaded at http://www.github.com/parkgilbong/Minhee_Analysis_Pack.        
  
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
