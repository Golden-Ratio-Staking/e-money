# Upgrade History

The below table can be used with [Cosmovisor v0.1.0](https://github.com/cosmos/cosmos-sdk/releases/tag/cosmovisor%2Fv0.1.0) to ensure a node can sync from genesis.

| Upgrade Plan   | Earliest Deployment Time   | Version                                                                    | Install Path                           | Notes                                |
| -------------- | -------------------------- | -------------------------------------------------------------------------- | -------------------------------------- | ------------------------------------ |
| -              |                            | [v1.1.0-RC2](https://github.com/e-money/em-ledger/releases/tag/v1.1.0-RC2) | cosmovisor/genesis/bin                 | Used at genesis                      |
| upgrade-plan-1 | 2021-09-18 at 13:00:00 UTC | [v1.1.1](https://github.com/e-money/em-ledger/releases/tag/v1.1.1)         | cosmovisor/upgrades/upgrade-plan-1/bin | Contains upgrade plan handler hotfix |
