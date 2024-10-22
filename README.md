# FWFS
Fourier Wavefront Sensor and E2E scheme implementation for "[Deep joint design in a Fourier-based wavefront sensor: a semi-analytical approach]()"

![ ](end2end_scheme.png)

# Requirements
The .yml file contains all required libraries to execute without problems in the repository. To install it, execute the following code to create a conda environment:
'''
conda create -n name -f environment.yml
'''

# Description
In the repository, you will encouter the main scripts in the path where you can execute them as they are, to recreate the figures from the article. 
The base functions, utilities, and others are located in the folders.

In order to recreate all the figures, execute the following commands on terminal:
'''
python3 test_rmse.py 
python3 test_sd.py
python3 test_D.py
python3 fig_DE.py
python3 test_prop.py
'''


# Citation
If you found this project useful, please cite us!
'''
@article{guzman2024deep,
  title={Deep optics preconditioner for modulation-free pyramid wavefront sensing},
  author={Guzm{\'a}n, Felipe and Tapia, Jorge and Weinberger, Camilo and Hern{\'a}ndez, Nicol{\'a}s and Bacca, Jorge and Neichel, Benoit and Vera, Esteban},
  journal={Photonics Research},
  volume={12},
  number={2},
  pages={301--312},
  year={2024},
  publisher={Optica Publishing Group}
}
'''

# Contact
You can contact Nicolás Hernández by sending an email to nicolas.hernandez@pucv.cl




