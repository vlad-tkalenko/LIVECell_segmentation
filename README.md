# LIVECell_segmentation
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
	python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
  	```
5. Pull dataset with dvc:
   	```
    	dvc pull
	```
