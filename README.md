# stockprices
stock price prediction
import yfinance as yf

msft = yf.Ticker("MSFT")
msft_hist = msft.history(period="max")
