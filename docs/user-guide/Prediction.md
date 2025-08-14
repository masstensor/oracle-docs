---
sidebar_position: 2
title: "What is a Prediction?"
---

## What is a Prediction?
A prediction is a forecast for a specific cryptocurrency's price movement from the prediction time to verify time(aka. duration). 

Prediction has a very important parameter: confidence level. A higher confidence level means more AI Agents will collaborate, which generally increases prediction accuracy. For example: 55% confidence engages 11 AI Agents with approximately 55% statistical accuracy, 60% confidence engages 17 AI Agents and 65% confidence engages 29 AI Agents. Since more agents require more computational resources, the cost will vary based on the selected confidence level.

Each prediction will output 3 key information:
- Prediction Time, the timestamp when prediction started.
- Start price, the target cryptocurrency price at prediction time.
- Trend, the whole price movement between prediction time and verify time, there are 2 possible trend: 
  - UP, the price at verify time great than start price
  - DOWN, the price at verify time less than start price

Currently we can only predict price movement in next 24 hours duration, longer duration prediction service will rollup soon.

## Prediction Accuracy
We trace the historic culmulative prediction accuracy for each cryptocurrency.

## Prediction Service
We provide 2 prediction services to connected users, these predictions can be used as you will.

### Free Predictions
Each day, the platform provides free predictions for major cryptocurrencies. Currently, BTC and ETH predictions at 60% confidence level are available daily. Our backend service will start the free prediction routines at 00:00 UTC everyday. But, because AI agents running need times and each cryptocurrency predict one by one, so the prediction time is not exactly at 00:00 UTC, you can check the start time of prediction by "Prediction Time" field.

Free prediction always predict next 24 hours price movement.

### Premium Predcitions
If you want to predict price movement of a cryptocurrency at some time you like, you can use our premium predciton service. Via premium prediction service, you can also predict price movement of another cryptocurrencies except BTC and ETH, currently we provide service for: BTC, ETH, SOL, BNB, OKB, XRP, ADA, AVAX, DOT, LINK, FIL, DOGE, SHIB, PEPE, ORDI, SUI, TON, BGB, HBAR, XLM, BCH, TRX, LTC, DAI, LEO, UNI, POL, HNT, DIMO, IOTX.