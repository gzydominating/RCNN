# RCNN

### Requirements: software

1. Requirements for Tensorflow(1.0 and so far)

2. Python(3.5) packages : 'tflearn', 'opencv3', 'skimage', 'PIL(pillow)', 'matplotlib', 'numpy', 'sklearn'

3. ImageNet dataset

### file introduce

1. selectivesearch.py : selective search source code

2. selectivesearch_example.py : example of selectivesearch

3. train_alexnet.py : pre-train for cnn model(alexnet, you can replace with vgg)

4. alexnet_test.py : test for cnn model

5. preprocessing_RCNN.py : some preproces

6. rp2file.py : save region proposal images to disk

7. fine_tune.py : fine-tune for cnn model use region proposal images

8. train_svm.py : train svm

9. detection_softmax_test.py : object detection use softmax

10. detection_svm_test.py : object detection use svm

### run

1. pre-train, $python train_alexnet.py

2. generate region proposal images, $python rp2file.py

3. fine-tune, $python fine_tune.py

4. train svm, $python train_svm.py

5. run detection, $python detection_softmax_test.py or detection_svm_test.py




