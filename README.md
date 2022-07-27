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



https://user-images.githubusercontent.com/110109850/181386026-b0268eec-bd41-4938-9d6b-e2ca93ef8197.mp4

