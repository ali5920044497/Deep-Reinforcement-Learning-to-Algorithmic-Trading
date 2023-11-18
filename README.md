# Deep-Reinforcement-Learning-to-Algorithmic-Trading
Project based on the framework developed by T. Théate and D. Ernst, modified to implement a PPO.

# Usage

Simulating (training and testing) a chosen supported algorithmic trading strategy on a chosen supported stock is performed by running the following command:

```bash
python main.py -strategy STRATEGY -stock STOCK
```

with:
* STRATEGY being the name of the trading strategy (by default PPO),
* STOCK being the name of the stock (by default Apple).

The performance of this algorithmic trading policy will be automatically displayed in the terminal, and some graphs will be generated and stored in the folder named "Figures".



# Citation

Experimental code supporting the results presented in the scientific research paper:
> Thibaut Théate and Damien Ernst. "An Application of Deep Reinforcement Learning to Algorithmic Trading." (2020).
> [[arxiv]](https://arxiv.org/abs/2004.06627)
