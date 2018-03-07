# Project Log



###  3.2

####P.1

- Follow the tutorial of Sentdex to develop an barcode detection by Tensorflow object detection API. 
- Creat GitHub repo and download Tensorflow moodels, protobuf.
- Follow the [installation](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md) and test the tutorial in jupyter notebook.

####P.2

- Running tensorflow on CPU with openCV streaming video and COCO dataset with the pre-trained model.
- Install the conda virtual env package for opencv and tensorflow

#### P.3 Customized object detection

- Find the dataset and lable it. I just download from sentdex's data.
- Use the labelling softwere like [labelimg](https://github.com/tzutalin/labelImg) on Github


### 3.5

#### P.4

- use datitran xml_to_csv.py and generat_tfrecord.py from [Github](https://github.com/datitran)
- Convert data xml to csv
- Install TF object detection module by setup.py and generate the tf_record. 

#### P.5

- Creat model or use pre-trained model and configuration file for deep learning.
- Configurate the training processe and train the model

#### P.6

- Export the model graph to .pd and test it

The TF.saver still cause the problem. The model is training but not saved to the model.ckpt.



### 3.7

Reinstall the Tensorflow and test the Object Detection with new dataset. It finally works!

