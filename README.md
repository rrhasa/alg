# StockBot

StockBot is a Python script for designing and testing your own daily stock trading algorithms.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install matplotlib and yfinance from your command line.

```bash
pip install matplotlib
pip install yfinance
```

## Usage
You will be asked to enter a ticker for the stock that you want to test the algorithm on.

If you want to modify the algorithm and design your own, you only need to change the Decide() method. That method takes three functions, and you can decide what those are or design your own inputs. My implementation uses moving averages and their derivatives/concavity (the class for which is set up for you to use in your own algorithm).

## Roadmap
The goal for this script is of course for it to be as robust and generalized as possible. To do this, one idea is to use Reinforcement Learning to fine tune the thresholds on the fly. If you have experience with ML or deep learning I very much encourage you to make conributions!!


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
