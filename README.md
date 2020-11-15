# comp541_Mask_R-CNN

Original cocoapi: https://github.com/cocodataset/cocoapi.git
To run julcocoDemo you need to first run "make" under cocoapi/PythonAPI

I needed to change the pycocotools/coco.py file to fix some type errors between Julia and Python.
You can find the changes commented around line 265.

If  you want to run the pycocoDemo please revert those changes.
