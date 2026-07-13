# EA-Risk-Manager-Panel-MT4

This EA provides a graphical interface for calculating the appropriate lot size based on account balance, stop loss distance, and risk percentage before placing a trade.

## Features

- Custom graphical user interface (GUI) panel
- Input Stop Loss distance in pips
- Input risk percentage
- Automatic account balance detection
- Calculate risk amount in USD
- Calculate recommended lot size
- Automatic adjustment based on broker lot limitations:
  - Minimum lot size
  - Maximum lot size
  - Lot step normalization

## User Interface

The panel displays:

- Current account balance
- Risk amount in USD
- Calculated lot size

## Technologies

- MQL4
- MetaTrader 4
- MT4 Standard Controls Library

## Screenshot

![EA Risk Manager Panel](Images/risk-manager-panel.png)

## Installation

1. Copy the `.mq4` file into:


MQL4/Experts/


2. Open MetaEditor and compile the file.
3. Attach the EA to a MetaTrader 4 chart.

## Project Type

Personal MQL4 Development Project

## Author

Leyla Khojasteh

