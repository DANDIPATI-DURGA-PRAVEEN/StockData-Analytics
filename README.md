# StockData Analytics

## Overview

Welcome to StockData Analytics! This project focuses on extracting, analyzing, and visualizing historical stock and revenue data for companies like Tesla and GameStop. Leverage Python, web scraping, Pandas, and Plotly to gain insights into financial trends and make data-driven decisions.

## Table of Contents

- [Project Overview](#project-overview)
- [Description](#description)
- [Skills Required](#skills-required)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Instructions](#instructions)
- [Contact](#contact)
- [About StockData Analytics](#about-stockdata-analytics)

## Project Overview

Welcome to StockData Analytics, where we delve into historical stock and revenue data for companies like Tesla and GameStop. This project utilizes Python, web scraping, Pandas, Plotly, and data analysis to extract, analyze, and visualize critical financial information. Explore interactive graphs and gain insights into the performance of these companies.

## Description

StockData Analytics focuses on the extraction, analysis, and visualization of historical stock and revenue data. By leveraging Python and web scraping, we obtain comprehensive insights into companies like Tesla and GameStop. The project aims to facilitate data-driven decision-making through interactive visualizations.

## Skills Required

- Python (Programming Language)
- Web Scraping
- Pandas
- Plotly
- Data Analysis

## Project Structure

### 1. Extracting Tesla Stock Data

Extracts historical stock data for Tesla, including opening and closing prices, high and low values, volume, dividends, and stock splits.

### 2. Extracting Tesla Revenue Data

Utilizes web scraping to fetch Tesla's revenue data, cleaning and formatting it for analysis.

### 3. Extracting GameStop Stock Data

Extracts historical stock data for GameStop using the `yfinance` library.

### 4. Extracting GameStop Revenue Data

Employs web scraping to extract revenue data for GameStop, following a process similar to Tesla.

### 5. Plotting Tesla Stock Graph

Visualizes the extracted Tesla stock data, including historical share prices and revenues, in an interactive graph titled "Tesla Stock Analysis."

### 6. Plotting GameStop Stock Graph

Visualizes the extracted GameStop stock data using the `make_graph` function, with the resulting graph titled "GameStop Stock Analysis."

## Getting Started

Before running the code, ensure you have the required libraries installed:

```bash
!pip install yfinance==0.1.67
!mamba install bs4==4.10.0 -y
!pip install nbformat==4.2.0
!pip install plotly --upgrade
