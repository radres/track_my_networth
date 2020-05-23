# Track My Net Worth
Simple app tracks your net worth including crypto assets.

## Installation
Install requirements by:
```
pip3 install -r requirements.txt
```

Make sure you can run the tests
```
python3 test_coinmarketcap.py
```

## Usage

Fill in the `cash_holdings.json` and `crypto_holdings.json` according to your holdings. You can only include the cryptos and currencies indicated below:

#### Currencies

```
PHP, HUF, IDR, TRY, RON, ISK, ILS, CNY, USD, EUR, PLN, GBP, CAD, AUD, MYR, NZD, CHF, HRK, SGD, DKK, BGN, CZK, BRL, JPY, KRW, INR, SEK, MXN, RUB, HKD, ZAR, THB, NOK, PHP, HUF, IDR, TRY, RON, ISK, ILS, CNY, USD, EUR, PLN, GBP, CAD, AUD, MYR, NZD, CHF, HRK, SGD, DKK, BGN, CZK, BRL, JPY, KRW, INR, SEK, MXN, RUB, HKD, ZAR, THB, NOK
```

Sample `cash_holdings.json` file:

```
{
    "USD":"100",
    "EUR":"200",
    "NOK":"300"
}
```

#### Cryptos

Sample `crypto_holdings.json` value:
```
{
    "bitcoin":"1.3",
    "ripple":"500",
    "decred":"23",
    "bitcoin-cash":"11"
}
```

After getting the json files in place, execute:

```
import total_worth

total_worth.save_total_worth()
```

now networth.txt should be recorded in the current directory

### To be added:
Different stocks and currencies


<img src="http://67.207.90.226/test.png"
     alt="Test"
     style="float: left; margin-right: 10px;" />
