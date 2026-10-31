# CustomTrex

Archive (`CustomTrex.tar.gz`) of a Linux build of the [T-Rex](https://github.com/trexminer/T-Rex) NVIDIA GPU miner, packed with ready-made start scripts. There is no source code here.

Archive contents:
- `CustomTrex`: the miner binary
- `<COIN>-<pool>.sh`: start scripts for ETH, ETC, RVN, CFX, XZC, SERO, VEIL and ETH+ZIL on pools such as ethermine, 2miners, nanopool, flexpool, woolypooly
- `config_example`: example JSON config (pools, worker name, HTTP API on port 4067)
- `README.md`: the upstream T-Rex documentation

## Usage
```bash
tar xzf CustomTrex.tar.gz && cd CustomTrex
mv CustomTrex t-rex          # the scripts call ./t-rex
./ETH-ethermine.sh
```
Put your own wallet address and worker name in the script or config before running.
