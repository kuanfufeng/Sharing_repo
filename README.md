# Sharing notebooks with examples

- USDA_geology - Plotting geological map and identifying where the input stations locate<br>
  (Please note that the notebook does not implement the geological unit color standards while plotting.)
- US-EPA_ecoregions - Mapping ecoregions map and identifying where the input stations are
- SensitivityKernels 
  
Geological source, https://datagateway.nrcs.usda.gov/GDGOrder.aspx#<br>
Ecoregions source, https://www.epa.gov/eco-research/ecoregions-north-america<br>
Sensitivity source, https://github.com/keurfonluu/disba<br>

-------
Create the environment
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

