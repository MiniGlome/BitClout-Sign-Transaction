![made-with-python](https://img.shields.io/badge/Made%20with-Python3-brightgreen)

# BitClout-Sign-Transaction
Python implementation of the BitClout signing algorithm.

## If you want to sign automaticaly

Include this in your code:
```python
from Sign_Transaction import Sign_Transaction

Sign_Transaction(seedHex, transactionHex)
```


The function `Sign_Transaction(seedHex, TransactionHex)` take as input the `seedHex` of the account that you can find in your LocalStorage and the `TransactionHex` you want to sign.


## If you want to sign manually

To sign a single transaction you can run the script from the command line whith the command: <br>
```python3 Sign_Transaction.py <seedHex> <TransactionHex>```
