# EA Pump and Dump ReadMe

Developer's site: [Forex Robot Easy](https://forexroboteasy.com)

Development: Forex Robot Easy Team

ForexRoboteasy.com

## Description

EA Pump and Dump is a trading expert advisor designed to analyze multiple assets simultaneously and execute trades based on the Pump and Dump strategy. The strategy aims to take advantage of strong price movements in the market.

The EA uses the iPump indicator to detect strong price movements. If a strong price movement is detected, the EA will check if the price is falling or rising and execute trades accordingly. If the price is falling, the EA will buy assets at a lower price, and if the price is rising, the EA will sell assets at a higher price.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## How it Works

1. The EA runs the `OnTick()` function on each tick of the market.
2. Inside the `OnTick()` function, it analyzes multiple assets simultaneously.
3. It checks if a strong price movement is detected using the `IsStrongPriceMovementDetected()` function.
4. If a strong price movement is detected, it checks if the price is falling or rising using the `IsPriceFallDetected()` and `IsPriceRiseDetected()` functions.
5. If the price is falling, it executes the `BuyAssets()` function to buy assets at a lower price.
6. If the price is rising, it executes the `SellAssets()` function to sell assets at a higher price.

## Function Details

### `IsStrongPriceMovementDetected()`

This function is responsible for detecting strong price movements using the iPump indicator. You can insert your code here to detect strong price movements. Return `true` if a strong price movement is detected, and `false` otherwise.

### `IsPriceFallDetected()`

This function is responsible for detecting price fall. Insert your code here to detect price fall. Return `true` if a price fall is detected, and `false` otherwise.

### `IsPriceRiseDetected()`

This function is responsible for detecting price rise. Insert your code here to detect price rise. Return `true` if a price rise is detected, and `false` otherwise.

### `BuyAssets()`

This function is responsible for buying assets at a lower price. Insert your code here to buy assets. After buying assets, a message 'Assets bought at a lower price' will be printed.

### `SellAssets()`

This function is responsible for selling assets at a higher price. Insert your code here to sell assets. After selling assets, a message 'Assets sold at a higher price' will be printed.

## Product Description

For detailed reviews and trading results of this product, visit [Forex Robot Easy - Review EA Pump and Dump for MT5](https://forexroboteasy.com/forex-robot-review/review-ea-pump-and-dump-for-mt5-a-professional-forex-traders-strategy-logic/).

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
