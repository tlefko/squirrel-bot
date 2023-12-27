# squirrel-bot
SQ Bot for Automated Bitcoin and SPX Trading

Hey guys -- I know many of you know me from my Hackintosh stuff but I have recently been expanding into different areas. I would love if you guys wanted to take the time to try this out :)


**Squirrel Strategy Setup Guide for Fully Automated Trading on BingX**

Introduction:

  This guide is designed to assist you in setting up a fully automated trading strategy using the Squirrel strategy on BingX. Follow each step carefully, and you'll have your strategy up and running in no time. 
  
  ***Account Registration***
  1. Visit BingX using this link: ](https://bingx.com/invite/NDD72ZWF) for a trading fee rebate. 
  2. Register with your real identity details. If you encounter access issues, consider using a VPN.
  3. 3. Once your account is set up, enable 2FA (Two-Factor Authentication) using your phone number or Google Authenticator for extra security.


  ***Accessing Strategy Interface***
  1. Click on this link after registration: [https://bingx.com/en-sa/signalTrade/](https://bingx.com/en-sa/signalTrade/).
  2. This will take you to the signal trade section where you can start setting up your strategy.
  
     Here, you'll configure the trading strategy page. These guide the bot on when to buy or sell. 2. Ensure you create a new “strategy”. This should be the second option on the page, vs a simple instruction. 3. Remember, the default settings for Take Profit (TP) and Stop Loss (SL) are usually fine, but feel free to adjust them if you have a specific strategy in mind. Modifying these is not recommended.


     ***Leverage Adjustment***
      1. Go to the BTCUSDT perpetual futures chart in your BingX account. 2. You'll see leverage sliders here. Adjust them to your desired level (default is usually 20x). Make sure the long and short sliders are at the same level. 3. Double-check your leverage settings to ensure they match your trading comfort level. Connecting to TradingView 1. After setting your leverage, return to your strategy setup on BingX. 2. You will get a TradingView alert message and a webhook. These are key for linking your BingX account to TradingView. 3. Save these details as you'll need them in the next steps.

     ***Setting Up in TradingView***
      1. Deposit your trading funds into PERPETUAL futures, not standard futures, for this strategy. 2. In TradingView, add your chosen trading indicator to the chart. 3. Adjust the settings based on your strategy and choose the timeframe you want the bot to operate in. 4. Create a new alert on the indicator. If you're setting this up while the bot is in a trade, pause the alert. 5. Wait for a specific market signal (like a red flag or yellow X) before enabling the alert. 6. In the alert settings, paste the message text and webhook you got from BingX.

     ***Final Configuration and Activation***
     1. Once you've set up the alert in TradingView, you can fine-tune the bot's settings. 2. Changes to the bot's timeframe or values will only take effect after you create a new alert. Conclusion You've now set up a fully automated trading strategy using the Squirrel strategy on BingX. Remember to review and adjust your strategy periodically. If you need help, reach out to BingX
