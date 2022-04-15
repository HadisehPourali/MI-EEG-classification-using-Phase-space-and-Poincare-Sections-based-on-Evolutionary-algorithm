# MI-EEG-classification-using-Phase-space-and-Poincare-Sections-based-on-Evolutionary-algorithm
classification of Motor Imagery signals using phase space and Poincare sections

# Background
Brain-Computer Interface (BCI) based on Motor Imagery (MI) is one of the emerging technology that has been used in smart healthcare applications that help disables connect with the real world by imagining a specific movement in the brain.

The code in this repository analyze MI-EEG data and classify imaginary movements of subjects. The subject imagined one of the corresponding movements: left hand, right hand, and foot. 

# Data Set
BCI Competition IV Dataset 1: http://www.bbci.de/competition/iv/

# Method
In this research, some novel features are presented for the classification of electroencephalography (EEG) signals. This feature is extracted based on the phase space reconstructed by the filtered signal using CSP. In the proposed method, we fit Poincaré sections in phase space to analyze data trajectory. The hyperparameters of Phase Space Reconstruction (PSR) and Poincaré sections are learned with Evolutionary Algorithm (EA). Finally, statistical features are extracted from the Poincaré intersection points are given for classification.

# Result
The proposed method is implemented on two public datasets that are BCI Competition III Dataset Iva and BCI Competition IV Dataset 1, But the above code is implemented in accordance with second dataset, and have been achieved the accuracy of 89.76% and 71.87% on these two datasets, respectively.
