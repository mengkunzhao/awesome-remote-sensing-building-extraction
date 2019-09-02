# Awesome Remote Sensing Building Extraction [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

List of datasets, codes and contests related to remote sensing building extraction.The newest at the top of each category.
![](/2019-Deep-Instance-Segmentation-Network_2.png)



## 1. Dateset
- **Microsoft BuildingFootprints** [**Canada**](https://github.com/Microsoft/CanadianBuildingFootprints) **&** [**USA**](
https://github.com/microsoft/USBuildingFootprints) *(Microsoft, Mar 2019)*   
12.6mil (Canada) & 125.2mil (USA) building footprints, GeoJSON format, delineation based on Bing imagery using ResNet34 architecture.    

- [**Spacenet Challenge Round 4 - Off-nadir**](
https://spacenetchallenge.github.io/datasets/spacenet-OffNadir-summary.html) *(CosmiQ Works, DigitalGlobe, Radiant Solutions, AWS, Dec 2018)*   
126k building footprints (Atlanta), 27 WorldView 2 images (0.3m res.) from 7-54 degrees off-nadir angle. Bi-cubicly resampled to same number of pixels in each image to counter courser native resolution with higher off-nadir angles, Paper: [Weir et al. 2019](https://arxiv.org/abs/1903.12239)   

- [**Inria Aerial Image Labeling**](https://project.inria.fr/aerialimagelabeling/contest/) *(inria.fr)*  
Building footprint masks, RGB aerial imagery (0.3m res.), 5 cities  


## 2. Code





## 3. Contest

- [**xView 2 Building Damage Asessment Challenge**](https://xview2.org) *(DIUx, Nov 2019)*  
550k building footprints & 4 damage scale categories, 20 global locations and 7 disaster types (wildfire, landslides, dam collapses, volcanic eruptions, earthquakes/tsunamis, wind, flooding), Worldview-3 imagery (0.3m res.), pre-trained baseline model. Paper: [Gupta et al. 2019](http://openaccess.thecvf.com/content_CVPRW_2019/html/cv4gc/Gupta_Creating_xBD_A_Dataset_for_Assessing_Building_Damage_from_Satellite_CVPRW_2019_paper.html)

- [**CrowdAI Mapping Challenge**](https://www.crowdai.org/challenges/mapping-challenge) *(Humanity & Inclusion NGO, May 2018)*  
Buildings footprints, RGB satellite imagery, COCO data format

- [**DEEPGLOBE - 2018 Satellite Challange**](http://deepglobe.org/index.html) *(CVPR, Apr 2018)*  
Three challenge tracks: Road Extraction, Building Detection, Land cover classification, Paper: [Demir et al. 2018](https://arxiv.org/abs/1805.06561) 
 
- [**广东政务数据创新大赛—智能算法赛**](https://tianchi.aliyun.com/competition/entrance/231615/introduction) *(Alibaba et al.Nov 2017)*    
  使用2015年和2017年分别获取到的广东省某地的Quickbird卫星影像（包含蓝、绿、红和近红外四个波段），识别出两年之间新增的人工地上建筑物（不包括道路）。获胜团队的解决方案可以在[天池](https://tianchi.aliyun.com/forum/postDetail?postId=3527)官网上找到。

- [**Spacenet Challenge Round 2 - Buildings**](https://spacenetchallenge.github.io/datasets/spacenetBuildings-V2summary.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, May 2017)*  
685k building footprints, 3/8band Worldview-3 imagery (0.3m res.), 5 cities, SpaceNet Challenge Asset Library   

- [**Spacenet Challenge Round 1 - Buildings**](https://spacenetchallenge.github.io/datasets/spacenetBuildings-V1summary.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, Jan 2017)*  
Building footprints (Rio de Janeiro), 3/8band Worldview-3 imagery (0.5m res.), SpaceNet Challenge Asset Library  
  




## Reference
- [Awesome Satellite Imagery Datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets)
- [Zhang Bin's Blog. remote sensing datasets](https://zhangbin0917.github.io/2018/06/12/%E9%81%A5%E6%84%9F%E6%95%B0%E6%8D%AE%E9%9B%86/)
- The picture of this page is from [Qi Wen et al.2019](https://www.mdpi.com/1424-8220/19/2/333/htm)
  


