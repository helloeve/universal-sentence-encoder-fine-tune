### Universal Sentence Encoder Fine Tuned

This repo provides a simple script which could export the [Universal Sentence Encoder](https://www.tensorflow.org/hub/modules/google/universal-sentence-encoder/1) to a model which could be fine tuned on new dataset.

To export the model, simply run the following command:

```
python convert_use.py
```

This will export the model to `model/`. The model file could be used in tensorflow serving and fine tuned on a new dataset. Look for `universal_sentence_encoder_fine_tune.ipynb` for a simple fine tuned classification task.