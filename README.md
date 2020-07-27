# mRunner
mRunner App support page

mRunner requires models in tflite format to run. You can either train your own models with TensorFlow and convert it to a tflite file (see [this](convertToTflite.ipynb) jupyter notebook) or download ready-made models. For accurate predictions, it is recommended to attach all pre- and postprocessing information as well as labels with TensorFlow metadata to the model.

Instead of attaching metadata to your modelfiles, you can use json init files to configure your model. A sample init file can be found [here](sampleInit.json).

Several sample image classifiers in the tflite format can be downloaded from [TFHub](https://tfhub.dev/s?deployment-format=lite&module-type=image-classification).
