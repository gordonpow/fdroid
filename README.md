# PiliBTRTV F-Droid repository

自架的 F-Droid 套件庫，APK 取自 [gordonpow/PiliBTRTV](https://github.com/gordonpow/PiliBTRTV/releases)（最新 3 版），由 GitHub Actions 每 6 小時（或手動）執行 `fdroid update` 並發布到 GitHub Pages。

- 套件庫網址：`https://gordonpow.github.io/fdroid/repo`
- 指紋（SHA-256）：`C721B842CCD732752B83521BCA679B59E8320645F3E39224A8A59BEB9511B9F4`
- 一鍵加入：https://gordonpow.github.io/fdroid/repo?fingerprint=C721B842CCD732752B83521BCA679B59E8320645F3E39224A8A59BEB9511B9F4

簽章金鑰不在此 repo；workflow 從 secrets（`FDROID_KEYSTORE_B64`、`FDROID_KEYSTORE_PASS`）還原。
