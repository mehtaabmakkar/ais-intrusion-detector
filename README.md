# ais-intrusion-detector
Network anomaly detection system modelled on thymic negative selection and clonal expansion, trained on NSL-KDD traffic data.

# AIS Intrusion Detector

Anomaly detection system inspired by T-cell development in the 
thymus. Normal network behaviour is defined as "self" — random 
detectors that match self are deleted (negative selection), and 
surviving detectors monitor live traffic for deviations. Clonal 
expansion strengthens detectors that catch confirmed attacks.

## Biological basis
- Negative selection → thymic censoring
- Match radius      → TCR affinity threshold  
- Clonal expansion  → affinity maturation
- Danger signals    → (planned)

## Dataset
NSL-KDD (cleaned KDD Cup 1999) — 125,000 labelled 
network connections across 52 features.

## Usage
pip install numpy pandas scikit-learn matplotlib
python ais_detector.py

## Results
N/A

## Background
Built as an exploration of Artificial Immune Systems (AIS) 
and their applications in cybersecurity.

Feel free to ask any questions!
Developed alongside the senior year of high school taking the IB Diploma and throughout my undergraduate studies at the University of British Columbia in Canada.
