# Data Summary


We split the [original xquad dataset](https://github.com/deepmind/xquad) into subsets.

There are 876/161/153 question-answer pairs from 34/7/7 articles for train/validation/test separately.

It is uploaded to [Hugging Face](https://huggingface.co/datasets/zhufy/xquad_split/tree/main) as well.

You can easily load it with the datasets library by:
```
from datasets import load_dataset
dataset = load_dataset("zhufy/xquad_split")
```
