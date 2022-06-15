

# Transformer classification experiment

## Training

### Transformer

```
python train.py --lr=0.1 --seed=42 --decay=1e-4 --batch-size 64 --model transformer --method mixup --epoch 100 --name mixup_transformer
```

### Baseline

```
python train.py --lr=0.1 --seed=42 --decay=1e-4 --batch-size 64 --model vgg --method mixup --epoch 100 --name mixup_vgg
```




