# MINDS
Multi-scale Information Diffusion Prediction with Sequential Hypergraphs

### Requirements
```python
pip install -r requirements.txt
```

### Setting
在 `run.py` 中设置， 数据集放在了`data`文件夹下
``` python
parser.add_argument('-dataset_name', default='christianity')
parser.add_argument('-epoch', default=50)
parser.add_argument('-batch_size', default=64)
parser.add_argument('-emb_dim', default=64)
parser.add_argument('-train_rate', default=0.8)
parser.add_argument('-valid_rate', default=0.1)
parser.add_argument('-lambda_loss', default=0.3)
parser.add_argument('-gamma_loss', default=0.05)
parser.add_argument('-max_seq_length', default=200)
parser.add_argument('-step_split', default=8)
parser.add_argument('-lr', default=0.001)
```

### Training

```python
python run.py
```

### Cite

Jiao, P., Chen, H., Bao, Q., Zhang, W., & Wu, H. (2024). Enhancing Multi-Scale Diffusion Prediction via Sequential Hypergraphs and Adversarial Learning. *Proceedings of the AAAI Conference on Artificial Intelligence*, *38*(8), 8571-8581.
