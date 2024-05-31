# LIVECell_segmentation
## Structure

* train.ipynb - contains code for training model

- inference.ipynb - contains code for validation and metrics

+ utils.py - contains some variables
## Installation
1. Create your new environment:
	```
	conda create --name YOUR_NAME python=3.9
	conda activate YOUR_NAME
	```
2. Clone repo:
	```
	git clone https://github.com/vlad-tkalenko/LIVECell_segmentation.git
	cd LIVECell_segmentation
	```
3. Install requirements:
	```
	pip install -r requirements.txt
	```
4. Install detectron2:
	```
	git clone https://github.com/facebookresearch/detectron2.git
	python -m pip install -e detectron2
  	```
5. Pull dataset with dvc:
   	```
    dvc pull
	```
