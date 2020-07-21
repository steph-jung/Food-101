# Food-101 Classification Challenge
This is an image classification challenge using [Food-101](http://data.vision.ee.ethz.ch/cvl/food-101.tar.gz) dataset.  
The prototype model which contains detailed explanations is [here](https://github.com/steph-jung/Food-101/blob/master/notebooks/SJ_Food_101_Modelling_tiny100_prototype.ipynb) and the model with the best result (0.9051) can be found [here](https://github.com/steph-jung/Food-101/blob/master/notebooks/SJ_Food_101_Modelling_Resizing.ipynb).

## Result

| Method | Epochs | Top-1  Accuracy |
|--------|--------|----------------|
| [Baseline Model](https://github.com/steph-jung/Food-101/blob/master/notebooks/SJ_Food_101_Modelling_tiny100_prototype.ipynb) | 17 | 0.8664 |
| [Progressive Resizing + TTA](https://github.com/steph-jung/Food-101/blob/master/notebooks/SJ_Food_101_Modelling_Resizing.ipynb) | 34 | 0.9051 |
| [Progressive Resizing + Mixup + TTA](https://github.com/steph-jung/Food-101/blob/master/notebooks/SJ_Food_101_Modelling_Resizing_Mixup.ipynb) | 34 | 0.9036 |
