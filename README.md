# CoinEx Chain 
chain_id: coinexdex

# How to setup node for chain_id: coinexdex
- please refer to [setup-guide](https://github.com/coinexchain/devops) but with following parameters:

# parameters
```shell
export CHAIN_ID=coinexdex
export CHAIN_SEEDS=
export ARTIFACTS_BASE_URL=https://github.com/coinexchain/artifacts/blob/master/coinexdex
export CETD_URL=${ARTIFACTS_BASE_URL}/linux_x86_64/cetd?raw=true
export CETCLI_URL=${ARTIFACTS_BASE_URL}/linux_x86_64/cetcli?raw=true
export GENESIS_URL=${ARTIFACTS_BASE_URL}/genesis.json?raw=true
export CETD_SERVICE_CONF_URL=${ARTIFACTS_BASE_URL}/cetd.service.example?raw=true
export SHA256SUM_CHECKSUM_URL=${ARTIFACTS_BASE_URL}/sha256.sum?raw=true
export EXPLORER_URL=explorer.coinex.org
```
