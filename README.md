# Sharing notebooks with examples

- USDA_geology - Plotting geological map and identifying where the input stations locate<br>
  (Please note that the notebook does not implement the geological unit color standards while plotting.)
- US-EPA_ecoregions - Mapping ecoregions map and identifying where the input stations are
- SensitivityKernels - Python scripts for surface wave depth - frequency sensitivities
- Monitoring_noiselevel_dev - Computing seismic velocity and attenuation changes of noise correlation functions (under [NoisePy](https://github.com/noisepy/NoisePy) environment)
  
Geological source, https://datagateway.nrcs.usda.gov/GDGOrder.aspx#<br>
Ecoregions source, https://www.epa.gov/eco-research/ecoregions-north-america<br>
Sensitivity source, https://github.com/keurfonluu/disba<br>

-------
Create the environment for USDA_geology/US-EPA_ecoregions/SensitivityKernels
```
conda create -n codetest python=3.9
conda activate codetest

pip install ipykernel
pip install numpy==1.26
pip install geopandas
pip install pandas
pip install fiona
pip install dbfread
pip install matplotlib
pip install disba
conda install -c conda-forge gmt
pip install pygmt
```
-------
Create the environment for Monitoring_noiselevel_dev
```
conda create -n noisepy -y python=3.10 pip
conda activate noisepy
pip install noisepy-seis
```
