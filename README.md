[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-lightgreen?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)


## Examples of satellite imagery using pytroll/satpy

Anaconda and Python ^3.7 required;   
EUMETSAT [PublicDecompWT](https://gitlab.eumetsat.int/open-source/PublicDecompWT) software required to decompress MSG HRIT/LRIT files;  
Sample data credits - EUMETSA portal - https://www.eumetsat.int/  
SEVIRI sensor description - https://www.eumetsat.int/seviri

-----

### Setup:

    git clone https://github.com/streltcov/satpy_samples.git
    cd satpy_samples/
    conda create -f environment.yaml

-----

### Notebooks:

* [ipyleaflet map (images resampled to EPSG:3857)](notebooks/folium_map.ipynb)
* [MSG3 resampling scene](notebooks/meteosat/MGS3_resample.ipynb)
* [MSG1 IR-1.6 and WV-7.3](notebooks/meteosat/MSG1_IR16_IR73.ipynb)
* [MSG1 IR-1.6 animation](notebooks/meteosat/MSG1_IR16_animation.ipynb)

-----

### Meteosat-10 (MSG3):
01-12-2016, HRIT | [notebook](notebooks/meteosat/MSG3_basic_scenes.ipynb)  
<br>
Colorized clouds | [full size tiff](images/msg/meteosat10/scene_1/colorized_clouds.tiff)   
<img src="images/png/meteosat10/scene_1/colorized_clouds.png" alt="colorized_clouds" width="580"/>  
Infrared 10.8 | [full size tiff]()  
<img src="images/png/meteosat10/scene_1/ir108.png" alt="infrared-108" width="580"/>  
Infrared clouds | [full size tiff]()  
<img src="images/png/meteosat10/scene_1/ir_clouds.png" alt="day" width="580"/>

### Meteosat-8 (MSG3):
01-12-2017, HRIT | [notebook](notebooks/meteosat/MSG3_basic_scenes.ipynb)  
<br>

IR-1.6 animation  
<video width="580" height="580" controls>
  <source src="images/IR_016_20170201_120010.mp4" type="video/mp4">
</video>
<br><br>
IR-1.6 | [full size tiff](images/msg/meteosat8/scene_1/ir_16.tiff)   
<img src="images/msg/meteosat8/scene_1/ir_16.png" alt="colorized_clouds" width="580"/>  
Water vapour - 7.3 | [full size tiff]()  
<img src="images/msg/meteosat8/scene_1/wv_73.png" alt="infrared-108" width="580"/> 
