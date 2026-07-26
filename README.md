# Kaggle Historical Options Data — backup part (Ram)

Part of a 5-repo split of the 9.2 GB Kaggle NIFTY/BankNifty intraday dataset
(compressed to ~1.5 GB, split into 91 MB chunks — GitHub caps files at 100 MB).

This repo holds parts: 12 13 14 15
All parts are spread across: Shakti, Dev, Krishna, Ram, Gori.

## Restore (need ALL parts from ALL 5 repos):
1. git clone each of the 5 repos
2. Put every kaggle_backup.tar.gz.partNN into ONE folder
3. cat kaggle_backup.tar.gz.part* | tar xzf -
   -> extracts the kaggle/ data folder
