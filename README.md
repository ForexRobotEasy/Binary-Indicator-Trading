# Binary Deal Trading ReadMe File

**Binary Deal Trading** is a custom trading indicator designed to optimize forex trades. It is developed by the Forex Robot Easy Team and more information about the product can be found on their website [forexroboteasy.com](https://forexroboteasy.com).

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Indicator Parameters](#indicator-parameters)
- [Pre-Signal Logic](#pre-signal-logic)
- [Confirmed Signal Logic](#confirmed-signal-logic)
- [Expiration Time](#expiration-time)
- [Overbought and Oversold](#overbought-and-oversold)
- [Reversal Point](#reversal-point)
- [Fractal Point](#fractal-point)
- [Disclaimer](#disclaimer)

## Introduction
The Binary Deal Trading indicator is built using the MQL library and is designed to provide optimized forex trading signals. It is developed by the Forex Robot Easy Team, a trusted name in the forex trading community. This ReadMe file provides an overview of the indicator's code and functionality.

## Installation
To use the Binary Deal Trading indicator, follow the steps below:
1. Copy the `Trade` library to the `MQL4` or `MQL5` folder in your MetaTrader installation directory.
2. Copy the indicator code to a new file and save it with the extension `.mqh`.
3. Include the indicator file in your expert advisor or custom indicator code using the `#include` directive.

## Usage
The Binary Deal Trading indicator can be used in an expert advisor or custom indicator to generate trading signals. It provides functions to check for pre-signals, confirmed signals, expiration time, overbought/oversold conditions, reversal points, and fractal points. These functions can be called from the `OnTick` function to perform the necessary trading actions.

## Indicator Parameters
The following constants are defined in the indicator code:

- `SYMBOL_NAME`: The symbol name to trade.
- `TIME_FRAME`: The time frame to use for analysis (0 for M1).
- `EXPIRATION_TIME`: The expiration time for trades in seconds (e.g., 900 for 15 minutes).

## Pre-Signal Logic
The `IsPreSignal` function is provided to check if there is a pre-signal available. This function should be customized with your specific pre-signal logic.

## Confirmed Signal Logic
The `IsConfirmedSignal` function is used to check if there is a confirmed signal available. This function should be customized with your specific confirmed signal logic.

## Expiration Time
The `HasExpired` function is used to check if the expiration time has passed for a signal. It takes the signal time as input and returns `true` if the current time minus the signal time is greater than the expiration time.

## Overbought and Oversold
The `IsOverbought` and `IsOversold` functions are provided to check if the current price is overbought or oversold, respectively. These functions should be customized with your specific overbought and oversold logic.

## Reversal Point
The `IsReversalPoint` function is used to check if there is a reversal point available. This function should be customized with your specific reversal point logic.

## Fractal Point
The `IsFractalPoint` function is provided to check if there is a fractal point available. This function should be customized with your specific fractal point logic.

## Disclaimer
Please note that Forex Robot Easy is not the official developer of the Binary Deal Trading indicator. This ReadMe file provides a sample code that can work based on the description of the product. To find the official developer and obtain detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/binary-deal-trading-indicator-review-optimize-forex-trades/). For any further assistance or customization of the indicator, please refer to the official developer or consult the MQL5 documentation.
