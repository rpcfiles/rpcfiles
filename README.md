# RonPaulCoin Archive

RonPaulCoin is a legacy cryptocurrency whose genesis block was created on December 23, 2013—exactly 100 years to the day after the passage of the Federal Reserve Act.

This repository serves as an archival mirror providing historical version 0.8.6.2 wallet builds from early 2014 for Windows and macOS, alongside modern configuration directives and validated ledger bootstrap archives.

---

## Resources & Links

* 🌐 **Live Gateway & Node:** [realtrueog.com](https://realtrueog.com)
* 💬 **Discord Chat:** [Join the RonPaulCoin Discord](https://discord.com/invite/CWJWaES44p)
* 🏛️ **Reddit Community:** [r/ronpaulcoin](https://reddit.com/r/ronpaulcoin)
* 📜 **Original Codebase (2013):** [ronpaulcoin/ronpaulcoin](https://github.com/ronpaulcoin/ronpaulcoin)
* 📦 **Blockchain Bootstrap Release:** [Download v2,221,495 (.zip)](https://github.com/rpcfiles/rpcfiles/releases/latest)

---

## Fast Sync Guide (Blockchain Bootstrap)

Syncing over 2.2 million blocks across peer-to-peer gossip can take days on legacy nodes. Using the pre-validated bootstrap snapshot (`blk00001.dat`–`blk00007.dat`) syncs your client in minutes.

1. Download **`RonPaulCoin-Bootstrap-blk-2221495.zip`** from the [Releases page](https://github.com/rpcfiles/rpcfiles/releases/latest).
2. Ensure your RonPaulCoin wallet or daemon is completely closed.
3. Extract all `.dat` files directly into your operating system's data directory:
   * **Windows:** `%APPDATA%\RonPaulCoin\`
   * **Linux:** `~/.ronpaulcoin/`
   * **macOS:** `~/Library/Application Support/RonPaulCoin/`
4. Relaunch your wallet. It will index directly off the local files instead of slowly requesting blocks across the network.

---

## Configuration Guide (`ronpaulcoin.conf`)

Before launching the wallet, ensure you have placed the active `ronpaulcoin.conf` into your data directory to connect directly with active consensus seed nodes.

### Windows Setup
1. Ensure your RonPaulCoin wallet is completely closed.
2. Open File Explorer and ensure **Hidden items** is checked under the View tab.
3. Navigate to your app data folder:
   ```text
   C:\Users\YOUR-USERNAME\AppData\Roaming\RonPaulCoin
