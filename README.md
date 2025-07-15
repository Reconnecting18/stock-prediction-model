# stock-prediction-model
Stock Dashboard that includes a prediction for future US Stock Market prices using a compilation of linear regression and news headlines.
- Based on Python Anaconda3
- Uses Streamlit and Plotly to display the dashboard and its UI elements (import streamlit as st; import plotly.express as px)
- Collects US Stock Price information live from Yahoo Finance (import yfinance as yf)
- Uses a Linear Regression algorithm to predict future stock prices (In the future, I plan to add in NLTK to analyze news headlines, but it's very complicated)
- Other imports include but not limited to:
    - import pandas as pd
    - import numpy as np
    - import asyncio
    - import aiohttp
    - import time
    - from sklearn.linear_model import LinearRegression
    - import nest_asyncio
    - import pandas_market_calendars as mcal
