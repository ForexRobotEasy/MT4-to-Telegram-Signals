# MT4 to Telegram Signals

MT4 to Telegram Signals is a code developed by the Forex Robot Easy Team to streamline forex trading by sending order notifications to a Telegram group. It allows traders to receive real-time updates on their MetaTrader 4 platform through the Telegram messaging app.

## How it works

The code connects to the Telegram API using the provided bot token and joins a specified Telegram group. It filters the symbols and magic numbers of the trading orders to only send notifications for the allowed ones. 

The message format is customizable, allowing traders to define how the order information is presented in the notification message. The default format includes the symbol, order type, price, and volume.

The code includes a function to capture a screenshot of the current chart and send it as an attachment in the Telegram group. Traders can use this function to share their trading setups or analysis with other group members.

## Usage

To use this code, follow these steps:

1. Replace `'YOUR_BOT_TOKEN'` with your Telegram bot token.
2. Replace `YOUR_CHAT_ID` with the chat ID of your Telegram group.
3. Replace `'YOUR_TELEGRAM_GROUP'` with the name or ID of your Telegram group.
4. Customize the `allowedSymbols` and `allowedMagicNumbers` arrays to include the symbols and magic numbers you want to receive notifications for.
5. Customize the `messageFormat` variable to define the order information format in the notification message.
6. Compile and run the code in your MetaTrader 4 platform.

## Additional Information

For more information about this product, including detailed reviews and trading results, visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mt4-to-telegram-signals-streamline-forex-trading/). 
Please note that Forex Robot Easy is not the official developer of this product. We only provide the sample code that can work as described in the product. To find the official developer of this product, please use MQL5.
