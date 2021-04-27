Simple plots that allows to do quick analysis using Tezos blockchain data about QuipuSwap smart contract storage. Powered by TzKT API.

### How to run:
1. Click [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ztepler/quipuswap-tezos-analysis-colab/blob/main/QuipuSwap_Tezos_Pool_Analysis.ipynb) to run notebook in Google Colab cloud (hold Ctrl to open colab in the new tab)

2. Choose token name in the dictionary inside "QuipuSwap contracts" cell. Insert this token name inside quotes in the next cell into the row with token variable:
```python
token = 'hDAO'
```
3. You may also change decimals count for selected token. To do this change the value of the row with token_decimals variable:
```python
token_decimals = 6
```
4. Select "Runtime" in the top bar menu and then click on "Run all". Another way to run cells is to manually select each cell one after another and run them using shift+enter combination
5. Wait a little and you should see new plots

### Also:
- If you want you can add another tokens. QuipuSwap v1.2 token factory can be found here: https://tzkt.io/KT1SwH9P1Tx8a58Mm6qBExQFTcy2rwZyZiXS/operations/ . You should pay attention for the rows with "created smart contract" captions. To add new token you need to add it to the tokens dictionary the name you like.
- If there are a long trade history in the smart contract, you can increase request depth (amount of requests to TzKT):
```python
requests_depth = 1
```

Have a nice exploration! Feel free to change / distribute / mint / burn.

----
@ztepler

