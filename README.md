***Parkinson's Disease Telemonitoring Analysis***
This project aims to explore a dataset of biomedical voice measurements from 42 individuals with early-stage Parkinson's disease who participated in a six-month trial of a telemonitoring device for remote symptom progression monitoring. The dataset contains 5,875 voice recordings with 26 attributes, including subject number, age, gender, time interval from baseline recruitment date, motor UPDRS, total UPDRS, and 16 biomedical voice measures.

**Dependencies**
This project requires the following dependencies to be installed:

pip install pandas
pip install seaborn
pip install matplotlib
pip install scipy

**Dataset**
The Parkinson's telemonitoring dataset was created by Athanasios Tsanas and Max Little of the University of Oxford, in collaboration with 10 medical centers in the US and Intel Corporation who developed the telemonitoring device to record the speech signals. The original study used a range of linear and nonlinear regression methods to predict the clinician's Parkinson's disease symptom score on the UPDRS scale.

subject#: unique identifier of the participant who took part in the study.

age: age of the participant in years.

sex: gender of the participant (0 = female, 1 = male).

test_time: time in seconds since the first measurement for each participant.

motor_UPDRS: score on the UPDRS III scale, which measures the severity of Parkinson's motor symptoms.

total_UPDRS: total score on the UPDRS scale, which measures the severity of Parkinson's symptoms overall.

Jitter(%): percentage of variation in time between vocal cycles during the production of a sustained vowel.

Jitter(Abs): absolute measure of variation in time between vocal cycles during the production of a sustained vowel.

Jitter:RAP: measure of variation in time between vocal cycles during the production of a sustained vowel, calculated by assessing the periodicity of cycles.

Jitter:PPQ5: measure of variation in time between vocal cycles during the production of a sustained vowel, calculated by assessing the periodicity of cycles.

Jitter:DDP: measure of variation in time between vocal cycles during the production of a sustained vowel, calculated by assessing the periodicity of cycles.

Shimmer: measure of the amplitude of vibration in the voice signal.

Shimmer(dB): measure of the amplitude of vibration in the voice signal in decibels.

Shimmer:APQ3: measure of the amplitude of vibration in the voice signal based on the first three harmonics.

Shimmer:APQ5: measure of the amplitude of vibration in the voice signal based on the first five harmonics.

Shimmer:APQ11: measure of the amplitude of vibration in the voice signal based on the first eleven harmonics.

Shimmer:DDA: measure of the absolute difference in amplitude between consecutive voice cycles.

NHR: Measure of the ratio between noise and harmonic components in the voice signal.

HNR: Measure of the ratio between the energy of the voice signal and the energy of the noise in the voice signal.

RPDE: Measure of the complexity of the voice pattern.

DFA: Measure of the ratio between short-term and long-term fluctuations in the voice signal.

PPE: Measure of the irregularity of the voice signal.
