## THU MIG's FEEDS Dataset
**FEEDS**(Face pEdestrian dEtection DataSet) is a data set specially used for pedestrian and face detection organized by the Multimedia Intelligent Group of School of Software，Tsinghua University. We extract part of the data from Pedestrian re-identification dataset such as PRW, CUHK and pedestrian detection data sets such as WIDER pedestrian, CrowdHuman, then we complete the pedestrian and face annotations. The figure below shows the number of pictures extracted from each data set.

![Source map of different datasets in different partition sets](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/source_map.PNG)

The dataset contains 12004 pictures with 118730 annotation boxes, including 28383 personal face annotation boxes and 90347 pedestrian annotation boxes. The training set, validation set and test set are divided according to the proportion of 5:1:4, including 6003, 1200 and 4801 pictures respectively. The number of dimensions for each set is shown in the following figure.

![The distribution of annotation quantity in different sets](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/refined_annos_distribution.PNG)

Drawing on the scale division method of KITTI and WIDER FACE datasets, the two categories are divided into three different scales according to the height of the annotation box: small (small), middle (medium) and large (large). The following is the ratio of the number of annotations in two different categories. The scale of object annotation is distinguished according to the pixel size of the object when the original image is scaled to 512 * 512.

![Annotation distribution map of dataset at different scales](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/refined_annos_distribution_dif_scale.PNG)
![Scale distribution of face annotation](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/refined_face_annos_scale_distribution.PNG)
![Scale distribution of pedestrian annotation](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/refined_ped_annos_scale_distribution.PNG)

## Download

[FEEDS train images](https://1drv.ms/u/s!ApP7S_U-jZ6UhF27RwzA17bu8Ff3?e=vCuno4)

[FEEDS val images](https://1drv.ms/u/s!ApP7S_U-jZ6UhFttEcmVcnNEDvgb?e=pJjw9d)

[FEEDS test images](https://1drv.ms/u/s!ApP7S_U-jZ6UhFwhl411NQZjlEKy?e=YqXoiX)

[FEEDS train annotations](https://1drv.ms/u/s!ApP7S_U-jZ6UhFl9nq9-C34YdG5c?e=R6Uqx9)

[FEEDS val annotations](https://1drv.ms/u/s!ApP7S_U-jZ6UhFYMWzpGOoITwY_N?e=Fd59H2)

[FEEDS test annotations](https://1drv.ms/u/s!ApP7S_U-jZ6UhFcZOqSxcaIumqBq?e=e06vz8)

## Benchmark
To be continue..

## Reference
[1] Zheng L,  Zhang H,  Sun S,  et al. Person re-identification in the wild. arXiv preprint arXiv:1604.02531, 2016.

[2] Xiao T , Li S , Wang B , et al. End-to-End Deep Learning for Person Search[J]. 2016.

[3]	Yang S, Luo P, Loy C C, et al. WIDER FACE: A Face Detection Benchmark[C]. computer vision and pattern recognition, 2016: 5525-5533.

[4] Shao S, Zhao Z, Li B, et al. CrowdHuman: A Benchmark for Detecting Human in a Crowd.[J]. arXiv: Computer Vision and Pattern Recognition, 2018.
