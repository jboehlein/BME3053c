# BME3053C: Glizzy Gators

## 1-Dimensional Signal Processing of Electrocardiograms to Diagnose Arrhythmia

### Authors: Jessica Boehlin, Estefania Urrego Hernandez, Tesneem Abdel-latif, Duc Tran 

### University of Florida

#### Info & Background
This project uses ECG data from the MIT-BIH Arrhythmia database [1]. The code has the aim to diagnose the irregular heartbeats of right bundle branch block (RBBB),
left bundle branch block (LBBB), premature ventricular contraction (PVC), premature atrial contraction (APC), tachycardia, and bradycardia, if present in the patient.
The code will only exammine the first 10 seconds of the ECG, although the readings extend to 10+ minutes of data. Although multiple file types can be downloaded from
the database, this code will utilize .dat files. 

#### Instructions
To begin, the user must have .dat files of the ECGs stored in the same matlab folder as the code. Once the code is opened, the user will click run in the upper right hand side of the screen. This will open up the file explorer tab where the user must select the .dat file of the patient they wish to assess. The output of this display the ECG (10 second interval) in graphical form. In addition, the code will print the patient's heartbeat, the type and time in which irregular heartbeats occur, and whether or not the patient has tachycardia or bradycardia. If the patient is negative for all of these conditions according to the ECG, the code will print that the patient is 'not at risk of arrhythmia'.

#### References
##### MIT-BIH Database:
[1] Moody GB, Mark RG. The impact of the MIT-BIH Arrhythmia Database. IEEE Eng in Med and Biol 20(3):45-50 (May-June 2001). (PMID: 11446209) 

##### Credit to introductory section that opens and reads .dat files of ECG data:
[2] Said BOUREZG (2020). Open_ECG: ECG .dat file reader (https://www.mathworks.com/matlabcentral/fileexchange/49822-open_ecg-ecg-dat-file-reader), MATLAB Central File Exchange. Retrieved December 13, 2020. 
