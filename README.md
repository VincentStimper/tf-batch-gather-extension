# tf-batch-gather-extension
This is an extension of the existing [tf.batch_gather] function. The new function is able to handle higher dimensional indices, such that
```
result[i1, ..., in, j1, ..., jm, k1, ...., kl] =
    params[i1, ..., in, indices[i1, ..., in, j1, ..., jm], k1, ..., kl]
```


[tf.batch_gather]: https://www.tensorflow.org/api_docs/python/tf/batch_gather
