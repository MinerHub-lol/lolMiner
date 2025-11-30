# lolMiner

**Next-generation multi-GPU miner for AMD • NVIDIA • Intel Arc**  
Best-in-class performance on Ethash • Etchash • Autolykos2 • Kaspa • Nexa • Iron Fish • Alephium • Pyrin • Radiant • Flux • Conflux

## Supported Algorithms & Dev Fee (2025)

| Algorithm            | Dev Fee | Primary Coins                     |
|----------------------|---------|-----------------------------------|
| etchash              | 0.7 %   | Ethereum Classic                  |
| ethash               | 0.7 %   | EthereumPoW, Larissa, Quai        |
| autolykos2           | 1.5 %   | Ergo                              |
| kaspa (heavyhash)    | 0.75 %  | Kaspa                             |
| nexa                 | 2.0 %   | Nexa                              |
| ironfish             | 1.0 %   | Iron Fish                         |
|  
| alephium (blake3)    | 0.75 %  | Alephium                          |
| pyrin                | 1.0 %   | Pyrin                             |
| radiant (sha512_256d)| 0.75 %  | Radiant                           |
| octopus              | 2.0 %   | Conflux                           |
| flux (zelhash)       | 1.0 %   | Flux                              |
| beamhashiii          | 1.0 %   | Beam                              |
| karlsen              | 1.0 %   | Karlsen                           |
| sha3x                | 1.0 %   | Tari                              |
| equihash 144.5/192.7/210.9 | 1.0 % | Zcash, Horizen, Komodo          |
| cuckatoo/cuckaroo    | 2.0 %   | Grin                              |

All fees are 60-second sessions only

## Dual & Triple Mining (very low extra fee)
- ETC + ALEPH (0.7 % + 0.0 %)
- ETC + KASPA (0.7 % + 0.0 %)
- ETHW + ZIL (0.7 % + 0.0 %)
- ERGO + KASPA (1.5 % + 0.0 %)
- IRON + RADIANT
- PYRIN + KASPA
- NEXA + ALEPHIUM

## Key Features
- Full 100 % LHR unlock on NVIDIA RTX 30xx/40xx/50xx series
- Dual and triple mining with independent intensity and OC per algo
- Extremely low stale share rate
- Advanced core/memory/power/fan overclocking via command line
- Temperature protection (auto-stop/start/reduce intensity)
- Powerful watchdog with custom scripts on crash
- Zombie-mode for 4–6 GB AMD cards on Linux (Etchash/Kaspa)
- Built-in HTTP + JSON API + simple web GUI
- Detailed stats (--longstats, --shortstats, --timeprint)
- JSON config files for easy to edit
- Fast pool reconnection and failover
- Works perfectly on HiveOS, RaveOS, minerstat, SimpleMining, Windows, Linux

## Supported GPUs
**AMD** — RX 9000/8000/7000/6000/5000 series, Vega, VII, Polaris, Big Navi, Navi  
**NVIDIA** — RTX 50xx, 40xx, 30xx (LHR fully unlocked), 20xx, 16xx, GTX 10xx, CMP  
**Intel Arc** — A770/A750/A580/A380 on most algorithms

## Quick Start Examples

**Etchash (ETC)**
```bat
lolminer --algo etchash --pool etc.2miners.com:1010 --user YOUR_WALLET.RIG001
