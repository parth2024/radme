# omarmmking-
pip install python-telegram-bot pandas requests
import requests
def get_real_time_data(symbol):
    # مثال باستخدام Binance API
    url = f"https://api.binance.com/api/v3/ticker/price?symbol={symbol}"
    response = requests.get(url)
    return float(response.json()['price'])
    python crypto_bot.py
    import requests
def get_real_time_data(symbol):
    # مثال باستخدام Binance API
    url = f"https://api.binance.com/api/v3/ticker/price?symbol={symbol}"
    response = requests.get(url)
    return float(response.json()['price'])
    def calculate_risk(recommendation):
    risk_reward = (recommendation['targets'][-1] - recommendation['entry']) / (recommendation['entry'] - recommendation['stop_loss'])
    return f"نسبة المخاطرة/العائد: {risk_reward:.2f}:1"
    
