---
sidebar_position: 2
title: "What is a Prediction?"
---

## What is a Prediction?
A prediction is an AI-generated forecast of a specific cryptocurrency’s price movement, covering the period from the prediction time to the verification time (also called the duration).

One key parameter of a prediction is the confidence level. A higher confidence level means more AI Agents will collaborate on the forecast, which generally improves accuracy. For example, a 55% confidence level engages 11 AI Agents with roughly 55% statistical accuracy, 60% confidence engages 17 AI Agents, and 65% confidence engages 29 AI Agents. Since more agents require greater computational resources, the cost increases with higher confidence levels.

Each prediction produces three key outputs:
- Prediction Time – the timestamp when the prediction was generated.
- Start Price – the cryptocurrency’s price at the prediction time.
- Trend – the overall price movement from prediction time to verification time, with two possible outcomes:
  - UP – the price at verification time is higher than the start price.
  - DOWN – the price at verification time is lower than the start price.

Currently, we can only predict price movements for the next 24-hour duration. Support for longer prediction periods will be rolled out soon.

## Prediction Accuracy
We track the historical cumulative prediction accuracy for each supported cryptocurrency.

## Prediction Service
We offer two types of prediction services for connected users. You can use these predictions however you wish.

### Free Predictions
Every day, the platform generates free predictions for major cryptocurrencies. Currently, BTC and ETH predictions are available daily at a 60% confidence level.
Our backend service begins the free prediction routine at 00:00 UTC each day. However, since AI agents require time to run and each cryptocurrency is processed sequentially, the actual prediction time may not be exactly at 00:00 UTC. You can check the exact prediction time in the **Prediction Time** field.

Free predictions always forecast price movements for the next 24 hours.

### Premium Predcitions
If you want to predict the price movement of a cryptocurrency at a specific time of your choice, you can use our Premium Prediction service.
With Premium Predictions, you can also forecast the price movements of cryptocurrencies beyond BTC and ETH. Currently supported assets include:
BTC, ETH, SOL, BNB, OKB, XRP, ADA, AVAX, DOT, LINK, FIL, DOGE, SHIB, PEPE, ORDI, SUI, TON, BGB, HBAR, XLM, BCH, TRX, LTC, DAI, LEO, UNI, POL, HNT, DIMO, IOTX.