# FIR-Image-Action-Localisation-Dataset

This dataset is an improved version of : https://github.com/visiongo-kr/FIR-Image-Action-Dataset
by : 
> Haoyu Zhang  
> noahzhang@hanyang.ac.kr  
> Visiongo Co., Ltd.
> 2020.06.23

We annotated the database with bounding boxes as well as a temporal syncronization RGB / IR and a cropping of the IR to reduce it to the field of view of the RGB.

For each video there are :
- BBOX : the folder containing the annotations
- IR : 24x32x1 images
- IR_cropped : IR images cropped to the RGB field of view
- IR_RGB : the RGB image with an IR overlay to check the spatial and temporal alignment 
- IR_RGB_BBOX : the RGB image with an IR overlay to check the spatial and temporal alignment with the ground truth
- RGB: 320x240x3 images
- video.mp4 : the IR_RGB video
- video_bbox.mp4 : the IR_RGB_BBOX video with the ground truth and action

# Demo on video1
## Annoations : bounding boxes & action
- Blue : Ground truth (on RGB)

https://user-images.githubusercontent.com/110109850/181387628-d37cf4ea-e6ef-4a32-ba6d-6d912ea2c35c.mp4

## Detection by SSD32
- Blue : Ground truth (on RGB)
- Green : SSD32 detection (on IR)

https://user-images.githubusercontent.com/110109850/181388452-6845fe01-39fc-4e76-8ab6-ea822881a505.mp4

# Actions

- 0 : sit
- 1 : stand
- 2 : walk
- 3 : fall
- 4 : lie
- 5 : standup
- 6 : sitdown
- 7 : lying
- 8 : sleeping
- 9 : falling
- 10 : falled
- 11 : active
