==================================
Object Detection 
==================================

The code in main contains the code needed to identify different types of candies. Code is inspired from https://huggingface.co/docs/transformers/tasks/object_detection. 

First, labels were made for the images in the "Candy Images" folder using Label Studio, click https://labelstud.io/guide/get_started.html for more information.

The annotated files were then exported, see the "Labelled Data" folder. The result file containing annotation information was converted to to the metadata file found in "Labelled Data\images" so that it was compatibale with Hugging Face.

YOLOS model (https://huggingface.co/docs/transformers/model_doc/yolos) was used to train the model

The model also does inference and counts the number of candies it finds. 
