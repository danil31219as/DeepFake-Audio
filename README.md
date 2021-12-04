# DeepFake-Audio

Was validated on APTLY lab's dataset 
http://www.eecs.yorku.ca/~bil/Datasets/for-rerec.tar.gz
| model              | file                               | pretrained  |  Metric |
| -------------------|:----------------------------------:| -----------:| -------:|
| Audio VGG16        | audio_vgg_classifier.ipynb         | False       | 0.9713  |
| ResNet101          | audio_pretrained_classifier.ipynb  | True        | 0.9956  |
| EfficientNet-b7    | audio_pretrained_classifier.ipynb  | True        | 0.9973  |
| ViT-B-16           | audio_pretrained_classifier.ipynb  | False       | 0.5593  |
| Wav2Vec Classifier | audio_transformer_classifier.ipynb | True        | 1.0000  |
