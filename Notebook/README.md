# GEFcom2012
NoteBook For Python

#### NoteBook
Define Model LSTM  for Wind Power Prediction
```python
    Net_model = NN_Net(params, x_train)
    scores = Net_model.train(x_train, y_train, x_test, y_test, 'wsPower2', load_models=False)
```

params please refer source Code and x_train,y_train