# UnstructedWorkEnvironmentDataset
#### Unstructed work environment data for __[Objects detection]__, __[Symantic segmentation]__, and __[Instance segmentation]__

## Dataset link
### https://drive.google.com/drive/folders/1hH0vD2f84ngYbmPteE6Hw21viorU81VC?usp=sharing

## The dataset is composed of 
### 8 classes of firefighting tools (RGBA images) for synthesize augmentation
<img src="https://github.com/moonjongsul/desk-environment-dataset/blob/main/desk_objects.png" width="800" height="450">

### + 8 classes of cooking objects (RGBA images)
<img src="https://github.com/moonjongsul/desk-environment-dataset/blob/main/cooking_objects.png" width="800" height="300">

### + Object detection dataset and state estimation dataset (synthesized dataset)
<img src="https://github.com/moonjongsul/desk-environment-dataset/blob/main/detection.png" width="800" height="350">


* * *
# Description of the dataset
## Structure
```
desk_environment_dataset
 ㄴ desk_objects
    ㄴ bin1
    ㄴ bin2
    ...
    ㄴ objects_state
 ㄴ cooking_objects
    ㄴ apple
    ㄴ eggplant
    ...
    ㄴ tongs
 ㄴ object_detection
    ㄴ cso5
       ㄴ Images
       ㄴ Labels
       ㄴ Masks
    ㄴ cso5_cocoform
       ㄴ train
       ㄴ train_annot
       ㄴ val
       ㄴ val_annot
 ㄴ state_estimation
    ㄴ cso5_aug     
       ㄴ train
       ㄴ test
    ㄴ cso5
       ㄴ train
       ㄴ test
 ㄴ semantic_segmentation
    ㄴ train
       ㄴ Annotations
       ㄴ images
       ㄴ labels
       ㄴ Masks
    ㄴ test    
       ㄴ Annotations
       ㄴ images
       ㄴ labels
       ㄴ Masks
```

## Files
```
objects: RGBA images and mask images of desk objects               # for synthetic augmentation
object_detection: Synthesis images for object detection            # for YOLO, EfficientDet, ... etc. 
state_estimation: Synthesis images for object state estimation     # for statenet
```
