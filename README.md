**Example EEG recordings for testing RELAX-Jr**

These are four example resting-state EEG recordings taken from young children that may be used as test data files for the RELAX-Jr pre-processing software. Files are in EEGLAB (.set) format and are 3 minutes in length with a sampling rate of 500 Hz. EEG was recorded using a Geodesic SensorNet while children watched videos. 

These files were taken from a larger open-access (CCO license) dataset on the OpenNeuro repository recorded by a seperate lab to our own ( for full details see: https://openneuro.org/datasets/ds004635/versions/3.0.0). These files provided here purely for the purpose of testing the RELAX-Jr software. 

To reduce file size, the files have been reduced in length (first 3 minutes of the recording), downsampled from 1 KHz to 500 Hz, and reduced from a 128 to 64 channel montage. No other pre-processing has been applied. 


*Below is a brief example of settings that might be used to clean the files using the RELAX-Jr GUI:*

<img width="1373" alt="relax_jr_example" src="https://github.com/user-attachments/assets/61425845-6eff-48be-8812-4d558af2cf7f">



Here is an example of some basic data inspection using EEGLAB for one of the raw (un-processed) files.

<img width="800" alt="Screenshot 2024-07-15 at 1 14 58 PM" src="https://github.com/user-attachments/assets/68e19314-c175-4418-8c84-d95bc902732e">


Here is an example of the same file after pre-processing with RELAX-Jr. 

<img width="800" alt="Screenshot 2024-07-15 at 1 15 22 PM" src="https://github.com/user-attachments/assets/ba2190d7-2827-4659-946c-2efda02ba5dd">
