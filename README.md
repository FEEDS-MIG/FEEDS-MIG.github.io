.markdown-body img { 
  /* 图片居中 */
  clear: both;
  margin: 0 auto;
  display: block;

  /* 添加图片阴影 */
  box-shadow:0px 1px 4px rgba(0,0,0,0.3),0 0 40px rgba(0,0,0,0.1) inset;
  webkit-box-shadow:0px 1px 4px rgba(0,0,0,0.3),0 0 40px rgba(0,0,0,0.1) inset;
  moz-box-shadow:0px 1px 4px rgba(0,0,0,0.3),0 0 40px rgba(0,0,0,0.1) inset;
  o-box-shadow:0px 1px 4px rgba(0,0,0,0.3),0 0 40px rgba(0,0,0,0.1) inset;
}
## THU MIG lab's FEEDS Dataset
**FEEDS**(Face pEdestrian dEtection DataSet) is a data set specially used for pedestrian and face detection organized by the Multimedia Intelligent Group of School of Software，Tsinghua University. We extract part of the data from Pedestrian re-identification dataset such as PRW, CUHK and pedestrian detection data sets such as WIDER pedestrian, CrowdHuman, then we complete the pedestrian and face annotations. The figure below shows the number of pictures extracted from each data set.

![Source map of different datasets in different partition sets](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/source_map.PNG)

The dataset contains 12004 pictures with 118730 annotation boxes, including 28383 personal face annotation boxes and 90347 pedestrian annotation boxes. The training set, validation set and test set are divided according to the proportion of 5:1:4, including 6003, 1200 and 4801 pictures respectively. The number of dimensions for each set is shown in the following figure.

![The distribution of annotation quantity in different sets](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/annos_distribution.PNG)

Drawing on the scale division method of KITTI and WIDER FACE datasets, the two categories are divided into three different scales according to the height of the annotation box: small (small), middle (medium) and large (large). The following is the ratio of the number of annotations in two different categories. The scale of object annotation is distinguished according to the pixel size of the object when the original image is scaled to 512 * 512.

![Annotation distribution map of dataset at different scales](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/annos_distribution_dif_scale.PNG)
![Scale distribution of face annotation](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/face_annos_scale_distribution.PNG)
![Scale distribution of pedestrian annotation](https://raw.githubusercontent.com/FEEDS-MIG/FEEDS-MIG.github.io/master/images/ped_annos_scale_distribution.PNG)

## Download

[FEEDS train images]()

[FEEDS val images]()

[FEEDS test images]()

[FEEDS train annotations]()

[FEEDS val annotations]()

[FEEDS test annotations]()

## Reference

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/FEEDS-MIG/FEEDS-MIG.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

