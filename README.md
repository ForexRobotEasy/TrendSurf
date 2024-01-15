# TrendSurf Expert Advisor ReadMe

This ReadMe file provides a description and explanation of the TrendSurf Expert Advisor code. TrendSurf is a trading robot designed to identify long-term trends in the Forex market and enter trades based on these trends.

## Overview

TrendSurf is developed by Forex Robot Easy Team and more information about the product can be found at [Forex Robot Easy](https://www.forexroboteasy.com). However, please note that ForexRobotEasy is not the official developer of this product and only provides a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.

The Expert Advisor works by analyzing long-term trends in the market and entering trades based on the identified trends. It uses a fixed stop loss level to manage risk and closes all open positions at a predefined time on Friday nights.

## Input Parameters

The Expert Advisor has the following input parameter:

- **StopLoss**: The fixed stop loss in pips.

## Global Variables

The Expert Advisor uses the following global variable:

- **fridayCloseTime**: The Friday night closing time.

## Expert Functions

The Expert Advisor consists of the following functions:

- **OnInit()**: This function is called during the initialization of the Expert Advisor. It sets the Friday night closing time.

- **OnDeinit(const int reason)**: This function is called during the deinitialization of the Expert Advisor. It closes any open positions.

- **OnTick()**: This function is called on every tick. It checks if it is time to close positions and closes them if necessary. It also checks for long-term trends and opens trades based on the identified trends.

- **CloseAllPositions()**: This function closes all open positions. It iterates through all open positions and closes them at the predefined stop loss level.

- **CheckLongTermTrend()**: This function checks for long-term trends. It analyzes the market data to determine if the long-term trend is up or down. It returns true if the long-term trend is up and false otherwise.

- **OpenLongTrade()**: This function opens a long trade. It executes the necessary code to open a long trade based on the identified long-term trend.

- **OpenShortTrade()**: This function opens a short trade. It executes the necessary code to open a short trade based on the identified long-term trend.

- **GetFridayCloseTime()**: This function gets the Friday night closing time. It calculates the Friday close time based on the current time and the number of days until Friday.

## Product Description

TrendSurf is a powerful Forex trading robot developed by Forex Robot Easy Team. It utilizes dual-logic algorithms to identify long-term trends in the Forex market and enter trades accordingly. The Expert Advisor is designed to provide big profits by capturing the most profitable market movements.

With TrendSurf, traders can automate their trading strategies and take advantage of long-term trends without the need for manual analysis. The Expert Advisor uses a fixed stop loss level to manage risk and ensures that all open positions are closed at a predefined time on Friday nights. This helps to protect profits and reduce exposure over the weekend.

For detailed reviews and trading results of TrendSurf, please visit [Forex Robot Easy - TrendSurf Review](https://forexroboteasy.com/forex-robot-review/trendsurf-review-dual-logic-forex-software-for-big-profits/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of TrendSurf, please refer to MQL5.

For more information about Forex Robot Easy and our other Forex trading products, please visit our website [Forex Robot Easy](https://www.forexroboteasy.com).
