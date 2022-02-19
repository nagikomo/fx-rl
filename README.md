# Example

### install package
```console
$ pip install ta
$ pip install MetaTrader5
```

### generate data
```console
$ cd data
$ python generate_data.py
```

### run agent
```console
$ python
```

```python
>>> from agent import dqn

>>> agent = dqn.Agent(model_name="efficientnet_b0", s=0, action_type=4, pip_scale=1, n=1, loss_cut=False, use_device="tpu", dueling=False)
>>> agent.run()
>>>
>>> self.plot_result(w=self.best_w, risk=0.04, s=self.s)
```
### argment
```python
"""
## s
  0 -> "EURUSD"
  1 -> "GBPUSD"
  2 -> "NZDUSD"
  3 -> "AUDUSD"
  4 -> "EURGBP"
  5 -> "GBPJPY"
  6 -> "USDJPY"
  7 -> "EURJPY"
  8 -> "AUDJPY"
  9 -> "NZDJPY"
  10 -> "USDCHF"
## Available is the model name
  efficientnet_b0 ~ b7
  
"""
```
