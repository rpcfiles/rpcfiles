# RonPaulCoin Archive

RonPaulCoin is a legacy cryptocurrency whose genesis block was created on **December 23, 2013**. 

This repository serves as an archival mirror providing historical **version 0.8.6.2** wallet builds from early 2014 for Windows and macOS, alongside essential configuration files.

---

## Resources & Links

* 💬 **Bitcointalk Thread:** [Topic 515946](https://bitcointalk.org/index.php?topic=515946)
* 📊 **Block Explorer:** [explorer.scrypt.ovh/ronpaulcoin](http://explorer.scrypt.ovh/ronpaulcoin) *(Currently offline in Europe)*
* 🌐 **Reddit Community:** [r/ronpaulcoin](https://www.reddit.com/r/ronpaulcoin)
* 💻 **Original GitHub:** [ronpaulcoin/ronpaulcoin](https://github.com/ronpaulcoin/ronpaulcoin)

---

## Configuration Guide (`ronpaulcoin.conf`)

Before installing the configuration file, launch your RonPaulCoin wallet for the very first time. Let it run and attempt to sync for a few seconds, then close the program to automatically generate the necessary application directories.

### Windows Setup

1. Ensure your RonPaulCoin wallet is completely closed.
2. Open File Explorer and enable **Hidden items** under the View tab.
3. Navigate to your app data folder:
   > `C:\Users\YOUR-USERNAME\AppData\Roaming\RonPaulCoin`
4. Copy the `ronpaulcoin.conf` file directly into this folder.
5. Re-open your RonPaulCoin wallet to begin synchronization.

### macOS Setup

1. Ensure your RonPaulCoin wallet is completely closed.
2. Open Finder, select the **Go** menu from the top menu bar, and choose **Go to Folder...**
3. Enter `~/Library` and click **Go**.
4. Open **Application Support**, then open the **RonPaulCoin** folder.
5. Copy the `ronpaulcoin.conf` file directly into this folder.
6. Re-open your RonPaulCoin wallet to begin synchronization.
