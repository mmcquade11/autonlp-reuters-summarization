---
title: Autonlp Reuters Summarization
emoji: 🤗
colorFrom: red
colorTo: gray
sdk: gradio
app_file: app.py
pinned: false
---

# Model Trained Using AutoNLP

- Problem type: Summarization
- Model ID: 34018133
- CO2 Emissions (in grams): 286.4350821612984

## Validation Metrics

- Loss: 1.1805976629257202
- Rouge1: 55.4013
- Rouge2: 30.8004
- RougeL: 52.57
- RougeLsum: 52.6103
- Gen Len: 15.3458

## Usage

You can use cURL to access this model:

```
$ curl -X POST -H "Authorization: Bearer YOUR_HUGGINGFACE_API_KEY" -H "Content-Type: application/json" -d '{"inputs": "I love AutoNLP"}' https://api-inference.huggingface.co/mmcquade11/autonlp-reuters-summarization-34018133
```
