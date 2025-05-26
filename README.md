# Attention-is-all-you-need
Implementation of "Attention is all you need" paper by Vaswani et al, 2017
This repository contains a sequence-to-sequence transformer model implemented in PyTorch to perform English to German translation. The model is trained on the [English to German Translation Dataset](https://www.kaggle.com/datasets/youssefelbadry10/english-to-germany) from Kaggle.
## Architecture:
![image](https://github.com/user-attachments/assets/70f2a50f-a006-4ada-b4b9-a4f79dcc8669)


##  Model Hyperparameters

The following hyperparameters are used to build and train the model:

| Hyperparameter   | Value     | Description                                  |
|------------------|-----------|----------------------------------------------|
| `n_emb`          | 256       | Embedding dimension                          |
| `vocab_size`     | 30000     | Vocabulary size for both languages           |
| `seq_len`        | 64        | Maximum sequence length                      |
| `batch_size`     | 64        | Number of samples per training batch         |
| `num_heads`      | 4         | Number of attention heads in transformer     |
| `n_dropout`      | 0.1       | Dropout rate for regularization              |
| `ffwd_w`         | 1024      | Feed-forward network hidden dimension        |
| `num_sa_blocks`  | 4         | Number of self-attention blocks (encoder)    |
| `num_ca_blocks`  | 4         | Number of cross-attention blocks (decoder)   |

Output :
![image](https://github.com/user-attachments/assets/113fe9dd-b4aa-4dec-a1f7-5ebcb0f9eef2)


