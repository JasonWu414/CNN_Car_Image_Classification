# CNN based Car Classification

### CNN is widely used in image classification. In this project, I am going to classify car images.

## dataset
stanford car dataset from https://ai.stanford.edu/~jkrause/cars/car_dataset.html

## How to use
#### download car dataset, prepare the data for the model.
#### download training image http://imagenet.stanford.edu/internal/car196/cars_train.tgz uncompress to ./data/cars_train
#### download testing image http://imagenet.stanford.edu/internal/car196/cars_test.tgz uncompress to ./data/cars_test
#### download devkit https://ai.stanford.edu/~jkrause/cars/car_devkit.tgz uncompress to ./data/devkit
#### download test annotation with class label http://imagenet.stanford.edu/internal/car196/cars_test_annos_withlabels.mat move it to ./data/devkit
#### (optional) download bounding box annotations for all images http://imagenet.stanford.edu/internal/car196/cars_annos.mat move it to ./data/devkit
#### run data_prepare.py to prepare the training and testing data for the model (you may need modify some paths in the file)
