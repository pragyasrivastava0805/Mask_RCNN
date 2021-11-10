# Mask R-CNN for Object Detection and Segmentation
Pragya Srivastava
Architecture of Mask-RCNN






![image](https://user-images.githubusercontent.com/65613793/141168247-7134d77b-f9c0-4c6c-863a-610123d9a177.png)









In the Model implemented in the Repo https://github.com/matterport/Mask_RCNN/ the feature maps output by FP2,FP3,FP4 and FP5 are P2,P3,P4,P5.To make the model robust,I introduced a Gaussian Noise layer with Standard deviation 0.1 in each of these.
I have committed the relevant changes needed to this repo.
Step 1:Download the MS Coco Dataset from http://images.cocodataset.org/zips/train2014.zip
                                         http://images.cocodataset.org/zips/val2014.zip
                                         http://images.cocodataset.org/zips/test2014.zip
 Step 2:Download pre-trained weights
 
 Step 3:cd Mask_RCNN/samples/coco
 Train using python3 coco.py train --dataset=/path/to/dataset --model=/path/to/pre-trained weights
 NoteBook Link https://colab.research.google.com/drive/1tzhUNHY4LI3qqCU313TkDBybAVLWPCB8?usp=sharing
