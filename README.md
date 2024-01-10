# Pairs Navigator MT5 ReadMe

This ReadMe file provides an overview of the code for the Pairs Navigator MT5 Expert Advisor. Please note that Forex Robot Easy Team is not the official developer of this product. We are only providing a sample code that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Pairs Navigator MT5 Review](https://forexroboteasy.com/forex-robot-review/pairs-navigator-mt5-review-streamline-forex-trading-with-ease/).

## Overview

The Pairs Navigator MT5 Expert Advisor is designed to streamline forex trading by providing a user-friendly interface for navigating between currency pairs. It creates a custom window called 'Pairs Navigator' where users can easily switch between charts of different currency pairs.

## Expert Initialization

The `OnInit()` function is the expert initialization function. It is called once when the expert is loaded onto the chart. In this function, the Pairs Navigator window is created using the `ChartOpen()` function. If the window creation fails, an error message is printed, and the initialization process is stopped.

The drag and drop functionality for currency pairs is enabled using the `ChartSetInteger()` function with the `CHART_PROPERTY_DRAG_TRADE` property.

## Expert Deinitialization

The `OnDeinit()` function is the expert deinitialization function. It is called when the expert is removed from the chart or the terminal is closed. In this function, all open charts in the Pairs Navigator window are closed using the `ChartClose()` function.

## Expert Tick

The `OnTick()` function is the expert tick function. It is called on each tick of the chart. In this function, it checks if a chart in the Pairs Navigator window is clicked by comparing the current chart ID with the main chart ID. If a chart is clicked, the symbol of the clicked currency pair is obtained using the `ChartSymbol()` function. Then, the expert navigates to the clicked chart using the `ChartNavigate()` function.

## Product Description

Pairs Navigator MT5 is an expert advisor designed to simplify forex trading by providing an intuitive interface for navigating between currency pairs. It allows traders to quickly switch between different charts without the need to search for and open individual charts manually.

Key Features:
- User-friendly interface for easy navigation between currency pairs.
- Drag and drop functionality for convenient chart management.
- Streamlines trading workflow and saves time.
- Compatible with MetaTrader 5 platform.

Please note that Forex Robot Easy Team is not the official developer of this product. We are showcasing a sample code that can work similarly to the described product. To find the official developer and obtain the complete and official version of this product, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Pairs Navigator MT5 Review](https://forexroboteasy.com/forex-robot-review/pairs-navigator-mt5-review-streamline-forex-trading-with-ease/).
