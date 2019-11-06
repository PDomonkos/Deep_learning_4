# Deep_learning_4

Get the data:

First download the validation.zip from here https://www.figure-eight.com/dataset/open-images-annotated-with-bounding-boxes/, then run the load_data.ipynb.

It will generate a folder structure with the images needed.

  0 => car
  
  1 => sport
  
  2 => dog

Train:

With the downloaded data, transfer_learning.ipynb can learn.
The logs of the previous train is also attached:

  log1.csv contains the results of the first training (layers in the base modell could not learn),
  
  log2.csv contains the second learning (some of the top layers could learn).
