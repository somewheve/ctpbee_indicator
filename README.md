# ctpbee_indicator

Here is the Indicator of [ctpbee](https://github.com/ctpbee/ctpbee)

### Quick Start

```python
from json import loads
from ctpbee.indicators  import Indicator
from ctpbee import CtpbeeApi

class Demo:
    def __init__(self, name):
        super().__init__(name)
        self.indicator = Indicator(450)
       


def read_json(json_name):
    with open(json_name, "r") as f:
        

 ``` 

Now it supports following indicators

- ma
- sma
- ema(self, data:object, period:int, alpha=None):
- wma
- kd
- macd
- rsi
- smma
- atr
- stdDev
- boll
- AroonIndicator
- UltimateOscillator
- trix
- roc
- mtm
- tema
- wr
- mean_dev
- cci
- sar
