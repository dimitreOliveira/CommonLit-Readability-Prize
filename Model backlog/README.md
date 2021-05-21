## Model backlog
- **Train** and **validation** are the splits using the train data from the competition.
- The competition metric is **RMSE**.
- **Public LB** is the Public Leaderboard score.
- **Private LB** is the Private Leaderboard score.

---

## Models

| Model | OOF | Public LB | Private LB |
|-------|-----|-----------|------------|
| 0-CommonLit-RoBERTa-base seq_256 TPUv3 | 0.5383 | 0.506 | ??? |
| 1-CommonLit-RoBERTa-base seq_256 TPUv2 | 0.6254 | 0.601 | ??? |
| 2-CommonLit-RoBERTa-base seq_300 TPUv3 | 0.5476 | 0.522 | ??? |
| 3-CommonLit-RoBERTa-large seq_256 | 0.7142 | 0.641 | ??? |
| 4-CommonLit-RoBERTa-large seq_300 | 0.6486 | ??? | ??? |
| 5-CommonLit-RoBERTa-base seq_256 base HP | 0.5458 | 0.526 | ??? |
| 6-CommonLit-RoBERTa-base seq_256 no_sampling | 0.5946 | ??? | ??? |
| 7-CommonLit-RoBERTa-base seq_256 sampling | 0.5370 | 0.533 | ??? |
| 8-CommonLit-RoBERTa-base seq_256 ep_50 | 0.5313 | 0.538 | ??? |
| 9-CommonLit-BERT-base seq_256 | 0.5258 | 0.528 | ??? |
| 10-CommonLit-BERT-base seq_256 | 0.5282 | 0.524 | ??? |
| 11-CommonLit-BERT-base seq_256 steo_10 | 0.5241 | 0.517 | ??? |
| 12-CommonLit-BERT-base seq_256 cls_token | 0.5400 | 0.533 | ??? |
| 13-CommonLit-RoBERTa-base seq_256 | 0.5470 | 0.542 | ??? |
| 14-CommonLit-RoBERTa-base seq_256 cls_token | 0.5223 | 0.525 | ??? |
| 15-CommonLit-RoBERTa-base seq_256 cls RAdam | 0.5294 | 0.545 | ??? |
| 16-CommonLit-RoBERTa-base seq_256 cls MAE | 0.5408 | 0.530 | ??? |
| 17-CommonLit-RoBERTa-base seq_256 cls bias_init | 0.5425 | 0.538 | ??? |
| 18-CommonLit-RoBERTa-base cls no_sampling | 0.5367 | 0.535 | ??? |
| 19-CommonLit-RoBERTa-base cls mean stddev | 0.5395 | 0.517 | ??? |
| 20-CommonLit-RoBERTa-base cls mean stddev sampled | 0.5501 | ??? | ??? |
| 21-CommonLit-RoBERTa-base cls mean stddev samp | 0.5183 | 0.527 | ??? |
| 22-CommonLit-RoBERTa-base cls 3_target MAE | 0.5283 | 0.532 | ??? |
| 23-CommonLit-RoBERTa-base cls 2_target | 0.5458 | 0.556 | ??? |
| 24-CommonLit-RoBERTa-base cls 3_target frozen embe | 0.5171 | 0.524 | ??? |
| 25-CommonLit-RoBERTa-base cls 3_target bs_32 | 0.5314 | 0.534 | ??? |
| 26-CommonLit-RoBERTa-base cls 3_tar bs_32 frozen | 0.5449 | 0.523 | ??? |
| 27-CommonLit-RoBERTa-base cls 3_tar hidden_11 | 0.5331 | 0.530 | ??? |
| 28-CommonLit-RoBERTa-base cls 3_tar linear | 0.5289 | 0.523 | ??? |
| 29-CommonLit-RoBERTa-base 1_target | 0.5473 | 0.542 | ??? |
| 30-CommonLit-RoBERTa-base 2_target | 0.5238 | 0.523 | ??? |
| 31-CommonLit-RoBERTa-base 2_tar 2x_stddev | 0.5366 | 0.532 | ??? |
| 32-CommonLit-RoBERTa-base aux_0 | 0.5377 | 0.545 | ??? |
| 33-CommonLit-RoBERTa-base aux_1 | 0.5474 | 0.536 | ??? |
| 34-CommonLit-RoBERTa-base aux_3_cats | 0.5435 | ??? | ??? |
| 35-CommonLit-RoBERTa-base aux_5_cats | 0.5137 | ??? | ??? |
| 36-CommonLit-RoBERTa-base aux_5_cats smoothing | 0.5295 | ??? | ??? |
| 37-CommonLit-RoBERTa-base aux_5_cats dropout | 0.5535 | ??? | ??? |
