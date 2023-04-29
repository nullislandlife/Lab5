# <B>Land-use & Land-cover Change Detection</B>


The importance of updated and consistent land use cartography is widely recognized. Land use cover changes (LUCC) are one of the most evident and fastest processes changing both the characteristics of land surface and the potential of natural ecosystems for provision of environmental services (Harold et al., 2009). Quality data about Land use cover (LUC) and LUCC are crucial to understanding the current and future dynamics of deforestation and its causes, including wildfires, urbanization, cropping, loss of biodiversity, and the influences on climate change (Harold et al., 2009; Radoux et al.,2014). This paper discusses (LUC) change detection (CD), the methods used to process spatial data, such as object detection, instance segmentation, and artificial neural networks, and how they apply to change detection.

In vision, the sensory stimulus processed is the light scattered from objects in a scene and projected in two-dimensional images. In computer vision (CV), an image is represented as an array of pixels, which is a two-dimensional function f (x; y) that returns the intensity recorded by a sensor at all points (x, y) of an image plane. The task of a computer vision system is to understand the scene that an image depicts (Esposito & Malerba, 2001). In an article, “Computer vision-enhanced selection of geo-tagged photos on social network sites for land classification,” published in the Journal of the International Environmental Modeling & Software Society, the authors built a classification model to filter relevant geo-tagged photos in social media sites using computer vision (ElQadi et al., 2020). The model generated descriptive tags to train an artificial neural network to predict a photo’s relevance for land cover classification. The team used Convolutional Neural Networks (CNNs) to classify geo-tagged photos from the Global Geo-Referenced Field Photo Library and Flickr into land cover classes. According to NVIDIA Developer Technical Blog, “Convolutional Neural Networks (CNNs) are a particular type of deep model responsible for many exciting recent results in computer vision” (Nvidia, 2014).

<img src="https://pub.mdpi-res.com/remotesensing/remotesensing-13-00364/article_deploy/html/images/remotesensing-13-00364-g010-550.jpg?" alt="Logo"> 

<i>Figure 1 Applications of Artificial Intelligence in Land Use and Land Cover Mapping.</i>

Deep learning, a type of machine learning, is based on artificial neural networks (ANNs), a class of robust and highly adaptable models that learn to extract and recognize complex patterns from large amounts of data (Esri, 2022). According to Esri, when applying deep learning to spatial data analysis, the modeling is divided into four main categories: object detection, instance segmentation, image classification, and pixel classification (Esri, 2022). For our purposes, we will focus on object detection and instance segmentation. Object detection, as the name implies, is about detecting objects. For example, one can train an algorithm to detect pedestrians, buildings, and automobiles. “Instance segmentation is about identifying the precise boundary of whatever feature we are trying to identify” (Esri, 2022). 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Detected-with-YOLO--Schreibtisch-mit-Objekten.jpg/1920px-Detected-with-YOLO--Schreibtisch-mit-Objekten.jpg" alt="Logo">

<i>Figure 2 Object detection</i>

<img src="https://production-media.paperswithcode.com/thumbnails/task/task-0000000003-d945c034_vTlkCrf.jpg" alt="Logo">

<i>Figure 3 Instance Segmentation</i>

Image Source: [Deep Occlusion-Aware Instance Segmentation with Overlapping BiLayers, CVPR'21](https://github.com/lkeab/BCNet)

Land cover change is regarded as one of the most important components of global change that also affects biological diversity, climate change, and terrestrial ecosystems (Vitousek, 1994). By monitoring and detecting changes in land use and cover, we can gain insights into how these factors affect the environment and help us develop strategies for mitigating their impacts. Traditional mapping techniques require manual work to classify land surfaces, thus making the work to provide consistent and timely datasets infeasible. Using land-use/cover change detection and spatial data processing techniques, such as artificial neural networks, we can better identify deforestation causes and subtleties.

<b>References</b>

Jean-François Mas, Richard Lemoine-Rodríguez, Rafael González-López, Jairo López-Sánchez, Andrés Piña-Garduño & Evelyn Herrera-Flores (2017) Land use/land cover change detection combining automatic processing and visual interpretation, European Journal of Remote Sensing, 50:1, 626-635, DOI: 10.1080/22797254.2017.1387505

Herold, M., Achard, F., deFries, R., & Mollicone, D. (2009, May 4–8). Earth observation and political negotiations: Linking requirements and capabilities in the context of the UNFCCC/REDD process. In Proceedings of the 33rd International Symposium on Remote Sensing of Environment (ISRSE) (pp. 1–4). Stresa, Italy.

Radoux, J., Lamarche, C., Van Bogaert, E., Bontemps, S., Brock- Mann, C., & Defourny, P. (2014). Automated training sample extraction for global land cover mapping. Remote Sensing, 6(5), 3965–3987.

Floriana Esposito & Donato Malerba (2001) Machine learning in computer vision, Applied Artificial Intelligence, 15:8, 693-705, DOI: 10.1080/088395101317018546

Moataz Medhat ElQadi, Myroslava Lesiv, Adrian G. Dyer, Alan Dorin,
Computer vision-enhanced selection of geo-tagged photos on social network sites for land cover classification, Environmental Modelling & Software, Volume 128, 2020, 104696, ISSN 1364-8152, https://doi.org/10.1016/j.envsoft.2020.104696.

“Deep Learning,” Esri, (accessed November 12, 2022), https://www.esri.com/training/mooc/player/5d76dcf7e9ccda09bef61294/61955f398a0a0c0da83dfb10/lessons/18662/

“Deep Learning for Computer Vision with Caffe and cuDNN,” NVIDIA, (accessed April 28, 2023), https://developer.nvidia.com/blog/deep-learning-computer-vision-caffe-cudnn/

Vitousek, Peter M. “Beyond Global Warming: Ecology and Global Change.” Ecology 75, no. 7 (1994): 1862–76. https://doi.org/10.2307/1941591.
