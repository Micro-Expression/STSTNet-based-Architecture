# STSTNet2 
Convolution3d with one parallel block

## Without Augmentation
`Train Time`: 5min 41.4sec
```
Epoch: 1/10, Loss: 83.6700764298439, Accuracy: 0.4010416666666667
Epoch: 1/10, Loss: 2.0001907348632812, Accuracy: 0.2857142857142857

Epoch: 10/10, Loss: 49.77988010644913, Accuracy: 0.5416666666666666
Epoch: 10/10, Loss: 1.211087703704834, Accuracy: 0.42857142857142855
```

## With Augmentation
`Train Time`: 5min 43.2sec
```
Epoch: 1/10, Loss: 95.16646015644073, Accuracy: 0.359375
Epoch: 1/10, Loss: 1.416420817375183, Accuracy: 0.25396825396825395

Epoch: 10/10, Loss: 63.18703004717827, Accuracy: 0.4791666666666667
Epoch: 10/10, Loss: 0.6842950582504272, Accuracy: 0.4126984126984127
```

# STSTNet
convolution3d with multiple prarallel block stacked together

## Without Augmentation
`Train Time`: 8min 2.2sec
```
Epoch: 1/10, Loss: 169.2735168337822, Accuracy: 0.34375
Epoch: 1/10, Loss: 1.8446950912475586, Accuracy: 0.2857142857142857

Epoch: 10/10, Loss: 70.99160099029541, Accuracy: 0.453125
Epoch: 10/10, Loss: 1.5393822193145752, Accuracy: 0.3492063492063492
```

## With Augmentation
`Train Time`: 8min 17.2sec
```
Epoch: 1/10, Loss: 194.9548265337944, Accuracy: 0.3333333333333333
Epoch: 1/10, Loss: 1.1748645305633545, Accuracy: 0.3492063492063492

Epoch: 10/10, Loss: 71.0024499297142, Accuracy: 0.4375
Epoch: 10/10, Loss: 2.072913646697998, Accuracy: 0.3333333333333333
```