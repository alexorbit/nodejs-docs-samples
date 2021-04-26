# Old SHND to New SHND \| StrongHands Documentation

**Quick Reminder: If you never swapped your coins never send them to an Exchange to trade, you will loose them!**

On 2018 Team decided to cut three zeros from total supply to guarantee inflation control since it was a big concern of our holders and newcomers.

The solution was a 1000:1 swap made internally in the blockchain. 100% of SHND were swapped successfully and **this will be the last swap of SHND in history**

Many people come to our forums thinking they lost coins in this process which is not true. If you have SHND in old QT's you can recover them back easily.

## [\#]()If you have unswapped coins there is a procedures to be done as follows:

1. First open your wallet app and backup and keep a saved copy of your wallet. Then close your wallet app and make sure it's not running.
2. Locate your StrongHands Folder and delete everything that's in the StrongHands Folder except for these two files: **wallet.dat** and **stronghands.conf**

### [\#]()If you don't know how to find your StrongHands Folder, then here's instructions below for both WINDOWS OS and MAC OS:

#### [\#]()How to find your StrongHands Folder for WINDOWS OS:

 1. On your keyboard, press the "WINDOWS" and "R" keys at the same time.

 2. Then type this: %appdata%\StrongHands

 3. Then press Enter.

 This will take you directly into your StrongHands Folder.

#### [\#]()How to find your StrongHands Folder for MAC OS:

 1. First open your "Go To Folder" finder

 2. Then type this: ~/Library/Application Support/StrongHands

 3. Then press Enter.

 This will take you directly into your StrongHands Folder.

1. Download the bootstrap which is used to speed up the syncing for a wallet app from [Here](https://github.com/stronghands-oficial/assets/releases/tag/shnd-bootstrap-0.7.3.0)

   Copy everything from the bootstrap except for the "SHND Instructions text file" and paste them into your StrongHands Folder.

2. Add the addnodes to your stronghands.conf file. You can get the addnodes from [Here](https://github.com/stronghands-oficial/assets/raw/main/shnd-peers.dat)
3. You can delete the old wallet app that you've been using.  Then download the new wallet app from our website: [https://www.stronghands.info/](https://www.stronghands.info/)
4. Open your new wallet app and let it fully sync.
5. When your wallet app is fully synced, also check if your wallet app's blocks are up-to-date with the [Explorer Website](https://www.coinexplorer.net/SHND)
6. On your wallet app; click Help, then click Debug window, then click the Console Tab. Then type: **repairwallet** and press Enter.

   **After you have pressed Enter,**

* If the results say **"mismatched coins"**, then simply close your wallet app and restart it again.
* If the results say **"True"**, then there's nothing else to be done.

1. To clean up old transctions:

   **Windows:** With wallet closed, open the Windows Terminal and paste +press enter the command: **C:\Users\User&gt; C:\stronghands-qt.exe -zapwallettxes**

   **MacOS:** open the terminal and paste+enter: **Open /Applications/Stronghands-Qt.app --args -zapwallettxes**

