# Fine-tunning-and-transfer-learning

In transfer learning we only train and optimize the weights of the newly added classification layers while we freeze the weights of the original model. Whereas, in fine tuning we train and optimize the weights of new classification layers as well as some or all layers from the model.

The DataLoaderandGenerator module is used to load new data for Tranfer Learning and Fine Tuning.

TransferLearning module is used to apply transfer learning on the pretrained VGG or mobilenet model.

The FineTuning module could be useful if the new model still doesn't perform well after the transfer learning phase.
