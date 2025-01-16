
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14582560.svg)](https://doi.org/10.5281/zenodo.14582560
**Real-Time Traffic Sign Recognition with Voice Assistance Using Optimized Curvelet Entropy Features**


**Authors:** Banhi Sanyal, Surja Sanyal

**Description:** 

This repository contains the Python and MATLAB code for the article  "**Real-Time Traffic Sign Recognition with Voice Assistance Using Optimized Curvelet Entropy Features**" under consideration in the journal "**The Visual Computer", Springer**.

**Files included:**

1. This project gives the article's codes with the same title.
2. The main file takes the dataset as input and computes all the coefficients of curvelet.

3. fdct_wrapping_window.m - Creates the two halves of a C^inf compactly supported window

 Inputs:
   x is  vector or matrix of abscissae, the relevant ones from 0 to 1

 Outputs:
   wl,wr  are vector or matrix containing samples of the left, resp. right
           half of the window

Used at least in fdct_wrapping.m and ifdct_wrapping.m

4. feature_vector_curvelet.m creates the 1D vector for the output from step 3.
5.  The py files are used for pre-processing  and the results are given in png files.

 **Datasets used:**
 
  ** a. [GTSRB}**: Publicly available dataset, can be downloaded at [https://benchmark.ini.rub.de/gtsrb_dataset.html](https://btsd.ethz.ch/shareddata/) and cited as under
  Stallkamp, J., Schlipsing, M., Salmen, J., Igel, C. Man vs. computer: Benchmarking machine learning algorithms for traffic sign recognition. Neural networks, 32, pp. 323-332 (2012).  https://doi.org/10.1016/j.neunet.2012.02.016
  
   **b. [BTSC]**: Publicly available dataset, can be downloaded at https://btsd.ethz.ch/shareddata and cited as under       
   Mathias, M., Timofte, R., Benenson, R., Van Gool, L. Traffic sign recognition—How far are we from the solution?. In The 2013 International Joint Conference on Neural networks (IJCNN) (pp.  1-8). IEEE (2013, August).  https://doi.org/10.1016/j.neunet.2012.02.016
 
   **c. [IRSDBv1.0]**  Sanyal, B., Mohapatra, R.K., Dash, R. (2020). Fully Annotated Indian Traffic Signs Database for Recognition. In Soft Computing: Theories and Applications. Advances in Intelligent Systems and Computing, vol 1154. Springer, Singapore. https://doi.org/10.1007/978-981-15-4032-5_63

7. The doi of code is DOI: 10.5281/zenodo.14582560

**Reproducibility**:


To reproduce the results from the article:

1. Download and set up the required datasets in the corresponding folders.
2. Ensure the required MATLAB toolboxes and python  are installed.
3. Run the  scripts with the appropriate dataset and parameters.


**Citation**

If you use this article or code in your research, please cite:

Real-Time Traffic Sign Recognition with Voice Assistance Using Optimized Curvelet Entropy Features

Journal = The Visual Computer (Under revision)
#Will be updated upon acceptance

