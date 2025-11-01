## Capstone project for ELEN-4830 (Digital Image Processing): Fingerprint Image Enhancement and Minutiae Extraction: Reproduction and Evaluation of Hong et al ###

### Files/Folders ###
1. final_project.ipynb: Project Code (Jupyter notebook)
2. data/raw/DB4_B: FVC2002 DB4 Fingerprint Dataset
3. data/raw/custom: Custom generated images for testing ridge orientation and Gabour Filter blocks
4. 102_5.pdf: Pipeline output for image 'data/raw/DB4_B/102_5.tif'
5. 102_6.pdf: Pipeline output for image 'data/raw/DB4_B/102_6.tif'
6. Report.pdf: Project Report 
7. ELEN4830-Fingerprint: Presentation slides

### Steps to run the final-project.ipynb:: ###
1.​ Open the folder: Project_Code in a code editor
2.​ Create a virtualenv or install required libraries given in cell-1
3.​ Enter a test_img path as 'data/raw/DB4_B/102_5.tif' (or any other image from the data directory)
4.​ Run ALL cells.

### References: ###
Implementations of the spectrogram and butterworth filters were referred from the following
sources:
1. L. Hong, Y. Wan, and A. K. Jain, “Fingerprint image
enhancement: Algorithm and performance evaluation,”
IEEE Transactions on Pattern Analysis and Machine
Intelligence, vol. 20, no.
2. https://github.com/Utkarsh-Deshmukh
3. https://github.com/robertvazan/fingerprint-datasets)
