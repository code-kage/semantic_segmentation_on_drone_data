# Semantic Drone Dataset

The Semantic Drone Dataset focuses on semantic understanding of urban scenes for increasing the safety of autonomous drone flight and landing procedures. The imagery depicts  more than 20 houses from nadir (bird's eye) view acquired at an altitude of 5 to 30 meters above ground. A high resolution camera was used to acquire images at a size of 6000x4000px (24Mpx). The training set contains 400 publicly available images and the test set is made up of 200 private images.

## Semantic Annotation

The images are labeled densely using polygons and contain the following 22 classes:
  
  - unlabeled
  - paved-area
  - dirt
  - grass
  - gravel
  - water
  - rocks
  - pool
  - vegetation
  - roof
  - wall
  - window
  - door
  - fence
  - fence-pole
  - person
  - dog
  - car
  - bicycle
  - tree
  - bald-tree
  - ar-marker
  - obstacle

## Included Data

* 400 training images
* Dense semantic annotations in png format can be 
    found in "training_set/gt/semantic/label_images/"
* Dense semantic annotations as LabelMe xml files can be 
    found in "training_set/gt/semantic/label_me_xml/"
* Semantic class definition can be 
    found in "training_set/gt/semantic/class_dict.csv" 
* Bounding boxes of persons as LabelMe xml files
    found "in training_set/gt/bounding_box/label_me_xml"
* Bounding boxes of persons as mask images
    found in "training_set/gt/bounding_box/masks"
* Bounding boxes of individual persons as mask images
    found in "training_set/gt/bounding_box/masks_instances"
* Bounding boxes of persons as python pickle file
    found in "training_set/gt/bounding_box/bounding_boxes/person/"


## Citation

www.dronedataset.icg.tugraz.at

