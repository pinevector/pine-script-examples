# PineVector Pine Script Examples

This repository contains example Pine Script indicators and trading strategies built for TradingView.

The goal of this project is to demonstrate different Pine Script implementations including:

- Custom indicators
- Trading strategies
- Alert systems
- Multi-indicator trading logic
- Strategy backtesting
- Risk management techniques

Project Structure

indicators
Examples of custom TradingView indicators.

strategies
Trading strategies that can be tested using the TradingView strategy tester.

systems
Examples of combining multiple indicators into a single trading system.

utilities
Reusable Pine Script modules and tools.

alerts
Examples of implementing TradingView alert conditions.

These scripts are designed as educational examples and starting points for building custom Pine Script systems.

---

## EMA Trend Indicator

This example demonstrates a simple trend-following indicator using fast and slow exponential moving averages.

### Features

- Trend detection using EMA crossover
- Buy/Sell signal markers
- Configurable inputs
- TradingView alert conditions

## RSI Divergence Detector

Pattern-based RSI divergence indicator with bullish and bearish signal labels and alert conditions.

### Features

- RSI calculation
- Bullish divergence detection
- Bearish divergence detection
- Signal labels
- Alerts

## Breakout Signal System

Price action breakout system using highest-high breakout logic with optional volume filtering and signal arrows.

### Features

- Highest high breakout
- Volume filter
- Signal arrows
- Alerts

## EMA Crossover Strategy

Example strategy demonstrating moving average crossover logic with configurable risk management.

### Features

- Entry logic
- Exit logic
- Stop loss
- Take profit
- Backtesting

## RSI Reversal Strategy

Oscillator-driven strategy focused on oversold entries and overbought exits with a protective stop.

### Features

- RSI oversold entry
- RSI overbought exit
- Stop loss
- Backtesting

## Multi Indicator Trading System

Combined system that requires trend, momentum, and breakout agreement before producing entries.

### Features

- EMA trend filter
- RSI momentum filter
- Breakout confirmation
- Combined signals

## Risk Management Module

Utility module to calculate stop-loss and take-profit levels and derive position size from account risk.

### Features

- Configurable stop loss
- Take profit
- Position size calculation

## TradingView Alert Template

Webhook-ready buy/sell alert template with JSON payload examples for automation pipelines.

### Features

- Buy alert
- Sell alert
- Webhook-ready alerts
