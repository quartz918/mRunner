# mRunner
mRunner App support page

mRunner requires models in tflite format to run. You can either train your own models with TensorFlow and convert it to a tflite file (see [this](convertToTflite.ipynb) jupyter notebook) or download ready-made models. It is recommended to attach all pre- and postprocessing as well as labels with TensorFlow metadata to the model.

Instead of attaching metadata to your modelfiles, you can use json init files to configure your model. A sample init file can be found [here](sampleInit.json).
