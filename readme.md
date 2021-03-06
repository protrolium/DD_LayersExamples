####Deepdream Layers Image Examples
Collection of images generated with the different layers from the *BVLC GoogleNet Model*. This might be useful for experimentation. The default settings from the google notebook are used.
https://github.com/google/deepdream


_________________
*source*

![default](https://raw.githubusercontent.com/gwio/DD_LayersExamples/master/images/clouds.jpg)

*pool3/3x3_s2*

![default](https://raw.githubusercontent.com/gwio/DD_LayersExamples/master/layers/pool3/3x3_s2/layers_pool3_3x3_s2_2015-07-05-19-33h.jpg)

*inception_5a/pool*

![default](https://raw.githubusercontent.com/gwio/DD_LayersExamples/master/layers/inception_5a/pool/layers_inception_5a_pool_2015-07-05-19-49h.jpg)

...

...

...

```
layer_list = [
"conv1/7x7_s2",
"pool1/3x3_s2",
"pool1/norm1",
"conv2/3x3_reduce",
"conv2/3x3",
"conv2/norm2",
"pool2/3x3_s2",
"inception_3a/1x1",
"inception_3a/3x3_reduce",
"inception_3a/3x3",
"inception_3a/5x5_reduce",
"inception_3a/5x5",
"inception_3a/pool",
"inception_3a/pool_proj",
"inception_3a/output",
"inception_3b/1x1",
"inception_3b/3x3_reduce",
"inception_3b/3x3",
"inception_3b/5x5_reduce",
"inception_3b/5x5",
"inception_3b/pool",
"inception_3b/pool_proj",
"inception_3b/output",
"pool3/3x3_s2",
"inception_4a/1x1",
"inception_4a/3x3_reduce",
"inception_4a/3x3",
"inception_4a/5x5_reduce",
"inception_4a/5x5",
"inception_4a/pool",
"inception_4a/pool_proj",
"inception_4a/output",
"inception_4b/1x1",
"inception_4b/3x3_reduce",
"inception_4b/3x3",
"inception_4b/5x5_reduce",
"inception_4b/5x5",
"inception_4b/pool",
"inception_4b/pool_proj",
"inception_4b/output",
"inception_4c/1x1",
"inception_4c/3x3_reduce",
"inception_4c/3x3",
"inception_4c/5x5_reduce",
"inception_4c/5x5",
"inception_4c/pool",
"inception_4c/pool_proj",
"inception_4c/output",
"inception_4d/1x1",
"inception_4d/3x3_reduce",
"inception_4d/3x3",
"inception_4d/5x5_reduce",
"inception_4d/5x5",
"inception_4d/pool",
"inception_4d/pool_proj",
"inception_4d/output",
"inception_4e/1x1",
"inception_4e/3x3_reduce",
"inception_4e/3x3",
"inception_4e/5x5_reduce",
"inception_4e/5x5",
"inception_4e/pool",
"inception_4e/pool_proj",
"inception_4e/output",
"pool4/3x3_s2",
"inception_5a/1x1",
"inception_5a/3x3_reduce",
"inception_5a/3x3",
"inception_5a/5x5_reduce",
"inception_5a/5x5",
"inception_5a/pool",
"inception_5a/pool_proj",
"inception_5a/output",
"inception_5b/1x1",
"inception_5b/3x3_reduce",
"inception_5b/3x3",
"inception_5b/5x5_reduce",
"inception_5b/5x5",
"inception_5b/pool",
"inception_5b/pool_proj",
"inception_5b/output"
]
```
