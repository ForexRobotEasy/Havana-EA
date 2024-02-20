# Havana EA

This is the code for Havana EA, an advanced forex software developed by Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product, but we are providing a sample code that can work as described in this product. For official development and support, please refer to MQL5.

For detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/havana-ea-review-advanced-forex-software-for-xauusd-trading/).

## Description

Havana EA is an expert advisor that operates in the forex market. It uses different entry models and trade management types to identify and manage trading opportunities. The code provided here demonstrates the basic structure and logic of the EA.

## Entry Models

The EA offers three entry models: MODEL_A, MODEL_B, and MODEL_C. The chosen entry model is specified in the `EntryModel` variable. The code implements different logic for each entry model to scan the forex market and identify entry opportunities.

## Trade Management Types

The EA also provides three trade management types: TYPE_X, TYPE_Y, and TYPE_Z. The chosen trade management type is specified in the `TradeManagementType` variable. The code implements different logic for each trade management type to implement an advanced trailing stop loss system and manage risk.

## Expert Initialization Function

The `OnInit` function is the expert initialization function. It is called once when the EA is initialized. In this function, the chosen entry model and trade management type are initialized and printed for reference.

## Expert Deinitialization Function

The `OnDeinit` function is the expert deinitialization function. It is called once when the EA is deinitialized. In this function, any necessary deinitialization tasks can be performed. A farewell message is also printed.

## Expert Tick Function

The `OnTick` function is the expert tick function. It is called on every tick of the forex market. In this function, the code scans the forex market based on the chosen entry model and implements the logic for entry and trade management. It also implements necessary trading functions and concludes the execution of the code with a message.

## Conclusion

This code provides a basic structure and logic for Havana EA. It demonstrates how the EA can scan the forex market, identify entry opportunities based on the chosen entry model, and implement an advanced trailing stop loss system based on the chosen trade management type. The code can be further customized and enhanced to suit specific trading strategies and requirements.

Please note that this code is a sample and not the official code developed by Forex Robot Easy Team. For official development and support, please refer to MQL5.
