# Bug/Vulnerability Description 🐞🔐

It is possible to execute ethereum transaction via authz module, bypassing maximum block gas limit, and effectively halt all nodes connected to the chain and chain itself.

This is done via cosmos-sdk authz module's exec. When /ethermint.evm.v1.MsgEthereumTx message is executed inside of /cosmos.authz.v1beta1.MsgExec message it bypasses most of eth transaction ante handler checks, gas limit check in particular. This allows executing ethereum transactions with basically any gas limit, without paying for it.

For demonstration purposes contract call with infinite loop was executed on testnet, which resulted in a halt of the chain.

<sub>Link to the original issue can be found [here](https://github.com/SigmaGmbH/swisstronik-evm-module/issues/11)</sub>

# Rewards 🏆🎉

2.000 USDT

1.000 USD worth of SWTR token

# Link to the transaction

<sub>(will be paid by the end of the bug bounty)</sub>
