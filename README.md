# **DRT_start_from_python**
DRT (Distribution of Relaxation Times) Analysis using Jupyter Notebook
A fast and easy to take Jupiter Note Book for DRT (distribution of relaxation time)

# Distribution of Relaxation time 
The aim of this document is to build an easy to understand python algorithm for DRT.

Welcome to this project repository! This Jupyter Notebook aims to showcase the algorithm for analyzing the Distribution of Relaxation Times (DRT) in multiple RC circuits. 

## **Table of Contents**

1. Introduction to the Voigt Circuit Function
2. Ridge Regression
3. Assistance & Improvements

---


## **1. Introduction to the Voigt Circuit Function**

In the domain of electrochemical impedance spectroscopy (EIS), the response of multiple RC (resistor-capacitor) circuits, both in series and parallel configurations, can be modeled as intricate electrical analogues representing the intricate physicochemical processes in the medium.

The Voigt circuit, often identified as a parallel RC circuit, stands as an archetypal representation in EIS. Its significance arises from its ability to transition insights from the frequency domain to the time domain, thereby elucidating the dynamic interplay in electrochemical systems.

Mathematically, the impedance of a parallel RC circuit (Voigt element) is given by:

\[
Z(\omega) = \frac{1}{\frac{1}{R} + j\omega C}
\]

Now, consider a large amount of serial RC. It's possible to see this situation as a infinite 'somme' (integrale) of a certain distribution function over a product which depend of tau (R*C) value for each serial RC.  

"Now, consider a series of numerous RC circuits. This situation can be viewed as an integration of a specific distribution function over the  τ (R*C) value for each RC circuit in series.

See : 
Schichlein, H., Müller, A. C., Voigts, M., Krügel, A., & Ivers-Tiffée, E. (2002). Deconvolution of electrochemical impedance spectra for the identification of electrode reaction mechanisms in solid oxide fuel cells. Journal of Applied Electrochemistry, 32, 875-882.


---



## **2. Ridge Regression**

Ridge regression is a type of linear regression that includes a regularization term. The regularization term discourages overly complex models which can lead to overfitting. The strength of the regularization is controlled by a parameter, often denoted as \( \lambda \). 

- To see how we started : 
https://www.youtube.com/watch?v=lJP8mQDyfPU&list=LL&index=5
and
https://www.youtube.com/watch?v=Nc01apG41bs&list=LL&index=6


## **3. Assistance & Improvements**

We believe in the power of collaborative development. If you have suggestions, improvements, or find any bugs, please feel free to raise an issue or submit a pull request. 

Whether you're a novice looking to learn or an expert with insights to share, your contributions are welcome. Together, we can enhance this project and make it a valuable resource for everyone. we target those part : 

- Work on the implementation of the DRT algorithm (Use the minimized function is not relevant)
- Work on the visualization of the DRT algorithm
- Charge of integrating Ridge Regression for robust DRT estimation.
- Assisted in data preprocessing and refining the Jupyter Notebook (maybe some matrix simplification).


## **Citations**

Voigt circuit : 

Orazem, M. E., Shukla, P., & Membrino, M. A. (2001). Extension of the measurement model approach for deconvolution of underlying distributions for impedance measurements. Department of Chemical Engineering, University of Florida. Received 10 August 2001; received in revised form 24 September 2001.

Meddings, N., Heinrich, M., Overney, F., Lee, J. S., Ruiz, V., Napolitano, E., ... & Park, J. (2020). Application of electrochemical impedance spectroscopy to commercial Li-ion cells: A review. Journal of Power Sources, 480, 228742.

DRT : 

Schichlein, H., Müller, A. C., Voigts, M., Krügel, A., & Ivers-Tiffée, E. (2002). Deconvolution of electrochemical impedance spectra for the identification of electrode reaction mechanisms in solid oxide fuel cells. Journal of Applied Electrochemistry, 32, 875-882.

Wan, T. H., Saccoccio, M., Chen, C., & Ciucci, F. (2015). Influence of the discretization methods on the distribution of relaxation times deconvolution: implementing radial basis functions with DRTtools. Electrochimica Acta, 184, 483-499.

Ramírez-Chavarría, R. G., Sánchez-Pérez, C., Romero-Ornelas, L., & Ramón-Gallegos, E. (2020). Time-constant-domain spectroscopy: an impedance-based method for sensing biological cells in suspension. IEEE Sensors Journal, 21(1), 185-192.

