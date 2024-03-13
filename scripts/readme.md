# SAMPLS: A prompt engineering approach for Plant Science research

## Dependencies

* PIL -                 9.4.0
* cv2 -                 4.8.0
* ipywidgets -         7.7.1
* matplotlib -        3.7.1
* numpy -              1.25.2
* pandas -             1.5.3
* session_info -       1.0.0
* skimage -            0.19.3
* torch -              2.1.0+cu121
* scipy -              1.11.4
* IPython -            7.34.0
* jupyter_client -     6.1.12
* jupyter_core -       5.7.1
* notebook -           6.5.5
* re
* math
* patchify
* transformers
* tifffile
* supervision
* segment_anyhting
* base64
* imagecodecs

## Scripts

Step 1: Running Vanilla SAM on images + prompt engineering

Step 2: Finetune SAM using results collected from Step 1 and finetuned prompt engineering

Step 3: Calculate the detection rate 

Step 4: IOU scores calculation

## Instructions

Step 1 can save pickle files of detected masks of any input confocal image using Vanilla SAM (VSAM) and prompt engineering. These masks need to be saved in your local system. These masks and images should then be loaded in step 2 for finetuning SAM for improved prompt engineering performance. Save the results from Finetuned-SAM as a pickle file and use these saved pickle files to determine the detection rates, iou scores in steps 3 and 4.

Some examples of input images, and their corresponding results from VSAM, Ft-SAM and PlantSeg are in folder "input_images_and_segmentation_results". Pickle files for these examples have not been provided. Please follow the instructions above to generate pickle files. 



