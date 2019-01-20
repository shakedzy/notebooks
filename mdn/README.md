This directory's notebooks contain Mixture Density Networks tutorial using Tensorflow.
* The `mdn` notebook includes the tutorial. This is the original notebook used for [this blogpost](https://engineering.taboola.com/predicting-probability-distributions/)
* The `mdn_with_tensorboard` notebook includes the same code as `mdn` with Tensorboard summaries
* The `mdn_low_level_api` notebook includes an older version of the code, using Tensorflow's low level API (instead of `tf.layers.dense` 
used in the other notebook). It also doen't include the text found in the `mdn` notebook

Read about MDNs in the [original paper](https://publications.aston.ac.uk/373/1/NCRG_94_004.pdf) by C. Bishop.
