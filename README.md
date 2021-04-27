Simple plots that allows to do quick analysis using Tezos blockchain data about QuipuSwap smart contract storage. Powered by TzKT API.

### How to run:
1. Click [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ztepler/quipuswap-tezos-analysis-colab/blob/main/QuipuSwap_Tezos_Pool_Analysis.ipynb) to run notebook in Google Colab cloud

2. Select one of the contracts from the dictionary in cell under "Requesting data" header. Just replace token name inside quotes in this row:
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
- If you want you can add another tokens. QuipuSwap v1.2 token factory can be found here: https://tzkt.io/KT1SwH9P1Tx8a58Mm6qBExQFTcy2rwZyZiXS/operations/ . You should look for rows with "created smart contract" captions. To add new token you need to add it to the tokens dictionary the name you like.
- If there are a lot of trades in smart contract, you can increase request depth (amount of requests to TzKT):
```python
requests_depth = 1
```
----
@ztepler

