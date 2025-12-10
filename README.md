# Aperiodic parameters of the fMRI power spectrum associate with preterm birth and neonatal age

Machine learning regression analysis predicting neonatal postmenstrual and postnatal age from aperiodic offset and exponent parameters of the resting-state fMRI BOLD signal

## Description

This repository provides code for data analysis of the Developing Human Connectome Project (dHCP) dataset, third data release (Edwards et al., 2022).
Detailed information about the dataset, including access instructions and terms of use, is available at: https://biomedia.github.io/dHCP-release-notes/

## Getting Started

Note: This repository does not include the dataset. To obtain the data, please follow the instructions provided in the dHCP Release Notes.

The analysis notebook contains hard-coded file paths. Before running the analysis, update these paths to point to the location of the dataset on your local machine.

### Installing and running the script

Recommendation: Create a dedicated virtual environment before running this notebook. This ensures that the required dependencies and specific package versions are installed without conflicting with other projects.

```
conda create -n my_env python=3.8.20
conda activate my_env
git clone https://github.com/ilksuu/fmri_aperiodic_parameters_age_prediction.git
cd fmri_aperiodic_parameters_age_prediction
pip install -r requirements.txt
jupyter notebook Aperiodic_parameters_of_the_fmri_power_spectrum_associate_with_preterm_birth_and_neonatal_age.ipynb
```

## Authors

Ilkka Suuronen (ilksuu@utu.fi)

## License

This project is licensed under the MIT License - see the LICENSE file for details

# Acknowledgments

**Dataset.** This work uses data from the Developing Human Connectome Project (dHCP, third data release). 
Please follow the instructions at https://biomedia.github.io/dHCP-release-notes to obtain access and cite the relevant dHCP publications in any derived work.

**Software.** We gratefully acknowledge the maintainers of the open-source libraries used in this project, including:
NumPy, pandas, scikit-learn, NeuroKit2 and FOOOF. See References for recommended citations.


# References

## dHCP dataset

- Edwards, A. D., Rueckert, D., Smith, S. M. et al. The Developing Human Connectome Project Neonatal Data Release. Front. Neurosci. 16, 886772 (2022).
- Hughes, E. J., Winchman, T., Padormo, F. et al. A dedicated neonatal brain imaging system. Magn. Reson. Med. 78, 794–804 (2017).
- Abo Seada, S., Price, A. N., Hajnal, J. V. & Malik, S. J. Optimized amplitude modulated multiband RF pulse design. Magn. Reson. Med. 78, 2185–2193 (2017).
- Fitzgibbon, S. P., Harrison, S. J., Jenkinson, M. et al. The dHCP automated resting-state functional processing framework for newborn infants. Neuroimage 223, 117303 (2020).
- Andersson, J. L. R., Hutton, C., Ashburner, J., Turner, R. & Friston, K. Modeling geometric deformations in EPI time series. Neuroimage 13, 903–919 (2001).
- Andersson, J. L. R., Skare, S. & Ashburner, J. How to correct susceptibility distortions in spin-echo EPI: application to diffusion tensor imaging. Neuroimage 20, 870–888 (2003).
- Andersson, J. L. R., Graham, M. S., Drobnjak, I., Zhang, H., Filippini, N. & Bastiani, M. Comprehensive framework for movement and distortion correction of diffusion MR images: Within-volume movement. Neuroimage 152, 450–466 (2017).
- Andersson, J. L. R., Graham, M. S., Drobnjak, I., Zhang, H. & Campbell, J. Susceptibility-induced distortion varying due to motion: Correction in diffusion MR without additional data. Neuroimage 171, 277–295 (2018).

## Python libraries

- Harris, C. R., Millman, K. J., van der Walt, S. J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). 
- McKinney, W. Data structures for statistical computing in Python. Proc. 9th Python in Science Conf. 51–56 (2010).
- Pedregosa, F., Varoquaux, G., Gramfort, A. et al. Scikit-learn: Machine learning in Python. J. Mach. Learn. Res. 12, 2825–2830 (2011).
- Makowski, D., Pham, T., Lau, Z. J. et al. NeuroKit2: A Python toolbox for neurophysiological signal processing. Behav. Res. Methods 53, 1689–1696 (2021). 
- Donoghue, T., Dominguez, J., Voytek, B. Parameterizing neural power spectra into periodic and aperiodic components. Nat. Neurosci. 23, 1655–1665 (2020).
