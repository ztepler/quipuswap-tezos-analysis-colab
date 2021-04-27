Simple plots that allows to do quick analysis using Tezos blockchain data about QuipuSwap smart contract storage. Powered by TzKT API.

### How to run:
1. Click [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ztepler/quipuswap-tezos-analysis-colab/blob/main/QuipuSwap_Tezos_Pool_Analysis.ipynb) to run notebook in Google Colab cloud (hold Ctrl to open colab in the new tab)

2. Choose token in the "Select token" form
3. Select "Runtime" in the top bar menu and then click on "Run all". Another way to run cells is to manually select each cell one after another and run them using shift+enter combination

### Also:
- If you want you can add another tokens. QuipuSwap v1.2 token factory can be found here: https://tzkt.io/KT1SwH9P1Tx8a58Mm6qBExQFTcy2rwZyZiXS/operations/ . You should pay attention for the rows with "created smart contract" captions. To add new token you need to add it to the tokens dictionary inside "QuipuSwap contracts" cell. Follow the available examples. The number after contract address is decimal, used in this token.
- If there are a long trade history in the smart contract, you can increase request depth (amount of requests to TzKT)

Have a nice exploration! Feel free to change / distribute / mint / burn.

----
@ztepler

