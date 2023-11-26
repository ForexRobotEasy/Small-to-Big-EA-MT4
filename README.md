# Small to Big EA MT4

This is the ReadMe file for the Small to Big EA MT4, developed by Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/small-to-big-ea-mt4-review-powerful-user-friendly-forex-software/).

## Description

The Small to Big EA is designed to perform automated trading operations in the foreign exchange market on the MetaTrader 4 platform. It uses a grid trading strategy and adjusts take profit and grid order distance dynamically based on exposure and volatility.

## Supported Currency Pairs

This EA supports the following currency pairs:
- AUDCAD
- AUDNZD

## Timeframe

The trading operations are performed on the H1 timeframe.

## Initialization

In the `OnInit` function, necessary indicators and variables are set up for the EA to function properly.

## EA Loop

The `OnTick` function is the main loop of the EA. It checks if the trading conditions are met, performs necessary calculations and analysis, and executes the trade.

## Trading Conditions

The `IsTradingConditionsMet` function implements the logic to check if the trading conditions are met. It returns true if the conditions are met, and false otherwise.

## Take Profit Calculation

The `CalculateTakeProfit` function calculates the dynamic take profit based on the current exposure and volatility. It returns the calculated take profit value.

## Grid Order Distance Calculation

The `CalculateGridOrderDistance` function calculates the dynamic grid order distance based on the number of trades and volatility. It returns the calculated grid order distance.

## Trade Execution

The `Trade` function performs the actual trade, using the calculated take profit and grid order distance. It also prints the trade details for logging and analysis purposes.

## Deinitialization

The `OnDeinit` function is called when the EA is being stopped or removed from the chart. It cleans up any resources used by the EA.

**Please note that ForexRobotEasy is not the official developer of this product. This code is only a sample that can work as described in the product. To find the official developer of this product, please use MQL5.**
