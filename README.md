[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-lightgreen?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Examples of satellite imagery using pytroll/satpy

Anaconda installation and Python ^3.7 required;   
EUMETSAT [PublicDecompWT](https://gitlab.eumetsat.int/open-source/PublicDecompWT) software required to decompress MSG HRIT/LRIT files;

-----

### Setup:

    git clone https://github.com/streltcov/satpy_samples.git
    cd satpy_samples/
    conda create -f environment.yaml

-----

[<h3>folium map</h3>](notebooks/folium_map.ipynb)

-----

### Meteosat-8 (MSG1):
<!-- [notebook](notebooks/meteosat/MSG3_basic_scenes.ipynb) -->
Colorized clouds | [notebook]() | [full size tiff](images/msg/meteosat10/scene_1/colorized_clouds.tiff)   
<img src="images/png/meteosat10/scene_1/colorized_clouds.png" alt="colorized_clouds" width="480"/>  
Infrared 10.8 | [notebook]() | [full size tiff]()  
<img src="images/png/meteosat10/scene_1/ir108.png" alt="infrared-108" width="480"/>  
Infrared clouds | [notebook]() | [full size tiff]()  
<img src="images/png/meteosat10/scene_1/ir_clouds.png" alt="day" width="480"/>