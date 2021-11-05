# Kucoin Volitility Trading Bot

## Description
This trading bot is a spin off from Binance Volatility Bot (BVT). Details of the BVT project is stated below.

The Kucoin trading bot analyses the changes in price across all coins on Kucoin and place trades on the most volatile ones. 
In addition to that, this Kucoin trading algorithm will also keep track of all the coins bought and sell them according to your specified Stop Loss and Take Profit.

The bot will listen to changes in price accross all coins on Kucoin. By default, we're only picking USDT pairs. We're excluding Margin (like BTCDOWNUSDT) and Fiat pairs

> Information below is an example and is all configurable

- The bot checks if the any coin has gone up by more than 3% in the last 5 minutes
- The bot will buy 100 USDT of the most volatile coins on Kucoin
- The bot will sell at 6% profit or 3% stop loss


You can follow the [Binance volatility bot guide](https://www.cryptomaton.org/2021/05/08/how-to-code-a-binance-trading-bot-that-detects-the-most-volatile-coins-on-binance/) for a step-by-step walkthrough of the bot development.

## READ BEFORE USE
1. If you use the `TEST_MODE: False` in your config, you will be using REAL money.
2. To ensure you do not do this, ALWAYS check the `TEST_MODE` configuration item in the config.yml file..
3. This is a framework for users to modify and adapt to their overall strategy and needs, and in no way a turn-key solution.
4. Depending on the current market, the default config might not do much, so you will have to adapt it to your own strategy.

## Usage
Please checkout our wiki pages:

- [Setup Guide](https://github.com/CyberPunkMetalHead/Binance-volatility-trading-bot/wiki/Setup-Guide)
- [Bot Strategy Guide](https://github.com/CyberPunkMetalHead/Binance-volatility-trading-bot/wiki/Bot-Strategy-Guide)
- [Configuration Guide](https://github.com/CyberPunkMetalHead/Binance-volatility-trading-bot/wiki/Configuration)

## Troubleshooting

1. Read the [FAQ](FAQ.md)
2. Open an issue / check us out on `#troubleshooting` at [Discord](https://discord.gg/buD27Dmvu3) 🚀 
    - Do not spam, do not berate, we are all humans like you, this is an open source project, not a full time job. 

## 💥 Disclaimer

All investment strategies and investments involve risk of loss. 
**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, 
and should not be construed as, a recommendation or as a guarantee of 
any specific outcome or profit.
By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.
