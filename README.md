# Dataset description
This is the repository for the Materials and Design paper titled "Texture-Sensitive Prediction of Micro-Spring Performance Using Gaussian Process Models Calibrated to Finite Element Simulations"
* There are separate datasets for the textures and elastic constants
* For the textures
  * Training set textures (440) and test set textures (22) are present in **texture.hdf5**
  * Characterization of the textures with GSH functions can be done through the PyMKS github page: https://github.com/materialsinnovation/pymks/blob/master/pymks/bases/gsh_functions/gsh_cub_tri_L0_16.py
* For the elastic constants
  * Training set elastic constants (440) and test set elastic constants (5) are present in **elastic-constants.mat**
* The FE simulations were performed using Sierra-XM solid mechanics suite and the spring constants were obtained as the slope of the load displacment curve
  * The spring constants are stored in **spring_constants.mat**
* Information about GPR model building can be found at Mathworks webpage on the same topic: [https://www.mathworks.com/help/stats/fitrgp.html]
