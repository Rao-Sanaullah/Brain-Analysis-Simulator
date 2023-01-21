
![Brain Analysis Simulator](https://github.com/Rao-Sanaullah/Brain-Analysis-Simulator/blob/main/image.png)

We believed that the development of Brain Analysis as an open-source brain tumor simulator with a user-friendly interface will help to advance our understanding of brain tumors and improve patient care. The runtime simulator allows researchers to fully understand each and every factor while executing the model, and to use a set of balanced values to accurately predict early brain tumors. On the other hand, we used a novel approach that involves a fast and accurate prediction of early brain tumor detection and region segmentation using a Random Forest Classifier ML model and a balanced statistical algorithm implementation.

Our proposed architecture is a novel tool that offers fully automated, user-independent analysis and simulation results, including state-of-the-art accuracy
and accurate tumor region segmentation of imbalanced MR images. In the proposed architecture, we used the following steps: first, various preprocessing algorithms (data cleaning, dimensionality reduction, feature engineering, imbalanced data, and data quality assessment) are applied to raw MR images to remove noise and other artifacts. Then, the watershed segmentation approach is used to segment the initial tumor region, and various features are extracted and analyzed from this segmented region. Finally, an SVM approach is applied to the resulting features for automated tumor classification. Overall, Brain Analysis represents a valuable tool in the field of medical image analysis and early brain tumor detection. Moreover, its open-source nature and run-time functionality make it a stand-alone simulator, and to the best of our knowledge, no other simulator offers these benefits. 

![Brain Analysis Simulator (Figure 1)](https://github.com/Rao-Sanaullah/Brain-Analysis-Simulator/blob/main/brain.jpg)

By making the simulator freely available for use by researchers, students, and medical professionals, the open-source characteristic opens up a wide range of possibilities for collaboration and integration with existing workflows. Furthermore, we believe that it can be utilized as an interactive tool for workshops and training sessions to help bridge the gap between research and practical application. Therefore, the Brain Analysis simulator opens up wide possibilities for collaboration and integration into existing workflows, making it a valuable tool for researchers and medical professionals. Figure 1 shows a basic structure of runtime Brain Analysis Simulator VI. 

Brain ANalysis Simulator is developed on a graphical programming language platform called LabVIEW (Laboratory Virtual Instrument Engineering Workbench)[1].


**Requirements**
- You need to have a graphical programming approach LabVIEW Runtime 2021 or above.
- A minimum computer requirement:
  
  • Processor: i3 CPU @ 2.3 GHz
  
  • RAM: 4.0 GB
  
  • System Type: 32/64-bit OS
  
  • Operating System: Mac OS, Window

To install Runtime LabVIEW:
https://www.ni.com/kokr/support/downloads/softwareproducts/download.labview.html#305931

And for further installation procedures please follow the Readme file located in the BrainANalysis.zip.

References:

[1]. NI LabVIEW, https://www.ni.com/de-de/shop/labview.html.


For any help, please contact

Sanaullah (sanaullah@fh-bielefeld.de)
