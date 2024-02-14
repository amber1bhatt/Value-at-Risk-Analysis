# Value at Risk (VaR) Analysis

This project provides a Python implementation of Value at Risk (VaR) analysis using Jupyter Notebook. VaR is a statistical measure used to quantify the potential loss in value of a portfolio or asset over a specified time period, at a certain confidence level. This analysis focuses on two commonly used VaR calculation methods: Parametric and Historic.

## Contents

1. [Introduction](#introduction)
2. [Methods](#methods)
3. [Results](#results)

## Introduction

Value at Risk (VaR) is a measure of the potential loss in value of a portfolio or asset over a specified time horizon, at a certain confidence level. It helps investors and risk managers understand the downside risk associated with their investments and make informed decisions.

This project implements two common methods for calculating VaR: Parametric and Historic. The Parametric method assumes a parametric distribution of returns, typically the normal distribution, while the Historic method uses historical observations of returns to estimate VaR directly.

## Methods

### Parametric Method

The Parametric method estimates VaR using a parametric distribution assumption, such as the normal distribution. It calculates VaR based on the mean and standard deviation of historical returns or other relevant parameters.

### Historic Method

The Historic method estimates VaR based on historical observations of asset returns. It ranks historical returns and calculates VaR based on the observed percentile of historical losses. The Historic method does not rely on distributional assumptions but captures historical market behavior directly.

## Results

The notebook presents the results of VaR analysis using both the Parametric and Historic methods. It includes visualizations, such as histograms and plots of VaR over different time periods, to illustrate the risk profiles of the analyzed assets.
