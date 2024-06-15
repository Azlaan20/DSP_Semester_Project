<p align="center">
  <img src="https://github.com/Azlaan20/DSP_Semester_Project/raw/main/Digital%20Signal%20Processing%20Project%20Report%20Cover.png" alt="Project Logo" width="500" height="600">
</p>
---

# Design and Implementation of Filters for EEG Signals using MATLAB

This repository contains the code and documentation for our Digital Signal Processing (DSP) Semester Project at NUST EME.

---

## Project Statement

Electroencephalography (EEG) is a critical diagnostic method that captures the brain's electrical activity through electrodes placed on the scalp. However, for effective analysis, EEG signals must be cleansed of various noise sources, including line noise. This project guides you through the application of Digital Signal Processing (DSP) techniques, focusing on signal filtering and noise reduction using MATLAB.

## Objectives

The goal of this project is to provide firsthand experience in managing, evaluating, and processing EEG data. Key objectives include:

- Learning to use MATLAB for EEG data processing.
- Detecting and removing line noise from EEG data.
- Designing and implementing various filters (notch, high pass, low pass, band pass) tailored to specific EEG frequency bands: delta (0.5-4 Hz), theta (4-7 Hz), alpha (8-12 Hz), sigma (12-16 Hz), and beta (13-30 Hz).
- Applying these filters to selected EEG channels.
- Documenting the entire process in a comprehensive report, including MATLAB code and graphical representations of EEG signals pre- and post-filtering.

## Dataset

The project utilized the `852_2_PD_REST.mat` file containing EEG data stored in a struct named `EEG`. The dataset's specifications and contents were essential for implementing the filtering techniques.

## Results Summary

The project successfully applied advanced digital signal processing techniques to EEG data:

- Implemented notch filters effectively removed 50Hz or 60Hz line noise, enhancing signal clarity.
- Designed and applied bandpass, high-pass, and low-pass filters to isolate specific EEG frequency bands (delta, theta, alpha, sigma, beta).
- Evaluated and compared the effectiveness of each filter in the time and frequency domains, demonstrating improved signal quality and noise reduction.
- Documented the filtering process and outcomes in a comprehensive report, providing insights into the application of DSP in EEG data analysis.

## Acknowledgements

This project was completed in collaboration with:
- Bilal Younas Chaudhary
- Rana Abdullah Azhar

## Contact Information

For more information, please contact:
- **LinkedIn**: [Azlaan Ranjha](https://www.linkedin.com/in/azlaan-ranjha-1b023a107/)
- **Email**: azlaanranjha2003@gmail.com

---
