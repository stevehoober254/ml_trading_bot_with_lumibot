# TraderBot

Build a trader bot which looks at sentiment of live news events and trades appropriately.

## Screenshots 📺

<img src="./screenshots/Screenshot_chart.png" alt=""/>

<img src="./screenshots/Screenshot_teardown.png" alt=""/>

## Startup 🚀

1. Create a virtual environment `conda create -n trader python=3.10`
2. Activate it `conda activate trader`
3. Install initial deps `pip install lumibot timedelta alpaca-trade-api==3.1.1`
4. Install transformers and friends `pip install torch torchvision torchaudio transformers`
5. Update the `API_KEY` and `API_SECRET` with values from your Alpaca account
6. Run the bot `python tradingbot.py`

<p>N.B. Torch installation instructions will vary depending on your operating system and hardware. See here for more:
<a href="pytorch.org/">PyTorch Installation Instructions</a></p>

## Other References 🔗

<p>-<a href="github.com/Lumiwealth/lumibot)">Lumibot</a>:trading bot library, makes lifecycle stuff easier .</p>
