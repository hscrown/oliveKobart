---
language:
- ko
metrics:
- bleu
library_name: transformers
tags:
- legal
- koBart
- summarization
---
oliveKobart is a language model specializing in summarizing Korean legal content. It was trained using criminal case verdicts from (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=580) and summaries created using the TextRank algorithm. It's fine-tuned from ainize/kobart-news(https://huggingface.co/ainize/kobart-news)
