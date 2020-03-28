# CoinEx Chain 
chain_id: `coinexdex`

# NOTES: <br> 
  - should add ` --minimum-gas-prices=20.0cet` in the `cetd start` command, both in validator and sentry nodes
    - example: <br> 
    > ${RUN_DIR}/cetd start --home=${RUN_DIR}/.cetd `--minimum-gas-prices=20.0cet` <br>

# How to setup node for chain_id: coinexdex
- please refer to [setup-guide](https://github.com/coinexchain/devops) but with following parameters:

# parameters
```shell
export CHAIN_ID=coinexdex
export CHAIN_SEEDS=9a379b9e1e41473d489de2470c02eac30fd4f77f@47.52.163.174:26656,01ac3646c649d91671173bd4aa02bc282ca804ba@47.252.23.106:26656
export ARTIFACTS_BASE_URL=https://coinexdex-artifacts.s3.amazonaws.com/coinexdex
export CETD_URL=${ARTIFACTS_BASE_URL}/linux_x86_64/cetd
export CETCLI_URL=${ARTIFACTS_BASE_URL}/linux_x86_64/cetcli
export GENESIS_URL=${ARTIFACTS_BASE_URL}/genesis.json
export CETD_SERVICE_CONF_URL=${ARTIFACTS_BASE_URL}/cetd.service.example
export SHA256SUM_CHECKSUM_URL=${ARTIFACTS_BASE_URL}/sha256.sum
export EXPLORER_URL=explorer.coinex.org
```
