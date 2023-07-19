![UAVSAR Flood Detection](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/title.png?raw=true)

<hr>

*Created by [**Clayton McLamb**](https://github.com/claytonmclamb) and [**Melvin Matias**](https://github.com/melvinmatias)*

*The work is funded by **NSF CNS-2149591** under the Research Experiences for Undergraduates (REU) [Program at Salisbury University](http://faculty.salisbury.edu/~ealu/reu/REU.html)*

<br>
<br>

<div align = "center">
  <p float="left">
    <img src="https://www.ncaa.com/sites/default/files/images/logos/schools/bgl/salisbury.svg" width="200" />
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/NSF.svg/2048px-NSF.svg.png" width="200" /> 
    <img src = "https://www.ncaa.com/sites/default/files/images/logos/schools/bgd/elon.svg" width="200"/>
    <img src = "https://logos-download.com/wp-content/uploads/2019/11/Drew_University_Logo.png" width = "200"/>
  </p>
</div>

<hr>

<a name="test"></a>
![Description](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/description.png)

Lorem ipsum dolor sit amet. A provident omnis qui nesciunt molestiae ea accusantium sapiente ut omnis cumque. Qui architecto velit et excepturi autem non consequatur temporibus vel autem voluptas eum corrupti perspiciatis! Eum nisi consectetur eos quia illo est unde ducimus eos fugiat laudantium cum earum eveniet quo repudiandae earum quo quam similique. Id accusamus cupiditate et aliquid provident non suscipit aliquid aut corporis atque qui veritatis itaque



<hr>

![Table of Contents](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/tableofcontents.png)
- [Packages & Tools Used](#packages)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)

<hr>

<a name="packages"></a>
![packages](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/tools.png)


| Tool | Use |
| :---: | --------- |
| ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) | test |
| ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)  | test |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) | test |
| ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) | test |
| <img src = "https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/assets/94720342/851cb85e-9c12-4864-80a7-851ba5c98e89" width = "60"> | test |
| ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) | test |
| <img src = "https://pythonfix.com/pkg/r/rasterio/rasterio-banner.webp" width = "60"> | test |
| <img src = "https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Google_Colaboratory_SVG_Logo.svg/2560px-Google_Colaboratory_SVG_Logo.svg.png" width = "60"> | test |
| <img src = "https://user-images.githubusercontent.com/12534576/192582340-4c9e4401-1fe6-4dbb-95bb-fdbba5493f61.png" width = "100"> | test |





<hr>


<a name="data"></a>
![data](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/data.png) <br><br>
The UAVSAR imagery used in our dataset was extracted from NASA's Jet Propulation Labratory's online UAVSAR imagery dataset. This dataset includes 11,619 POLSAR products from 1,674 different flights. The POL-SAR images include the HH, HV, and VV bands. For this project we will be using POL-SAR imagery from the aftermath of Hurricane Florence. The two specific areas and dates of interest are Lumberton, NC from September 18 2018 (Flight 18069), and Cape Fear, NC from September 22 2018 (Flight 18068). These dates were chosen to have a diverse enough dataset with a mix of a vareying flood levels.
<br><br>
Our dataset includes the images mentioned above along with hand labeled masks created with Label Studio. The segmentation masks are labeled 0 - No Water and 255 - Water, and was labeled with the aid of the NCONEMAP floodmap _Hurricane Florence Flood Extent Across the Piedmont and Coastal Plain of North Carolina_ as a reference. The data from NCONEMAP provides an estimate of inland flooding in North Carolina during Hurricane Florence. This work was able to detect flooded bodies of water by using a random forest classification model and by using pre- and post-storm SAR imagery from Sentinel-1, as well as general data on topography, and floodplains. The NCONEMAP model was trained with United States Geological Survey (USGS) and NCDEMS high-water marks. NCONEMAP was also cross referenced with high-resolution National Oceanic and Atmospheric Administration (NOAA) digital images.
<br><br>
Similarly to how the NCONEMAP flood map used NOAA digital images to serve as a guideline we too checked both our labeled masks and NCONEMAP with the digital imagery as a cross reference. Our dataset has a total of ____ images and masks.
<br>

<hr>



<a name="methods"></a>
![methods](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/methods.png)

<hr>

<a name="results"></a>
![results](https://github.com/claytonmclamb/REU-2023-UAVSAR-Flood-Detection/blob/main/Images/results.png)


