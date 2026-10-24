# 😈 KMJ TIPS — Toast Remote Config

Is repo ki `config.json` file KMJ TIPS Toast/Dialog ko control karti hai.
**Kabhi bhi control:** is file ko edit karke Commit kar do — agle app-open pe
sab users pe naya asar. Dex/APK dobara banane ki zaroorat nahi.

Raw link (dex me baked): https://raw.githubusercontent.com/KMJ-TIPS/kmj-toast/main/config.json

## Controls
- `"enabled": false` → dialog puri tarah OFF | `true` → ON
- `"show_dialog": false` → Update Required screen (sirf Update Now button)
- `"force_update_below": 5` → versionCode 5 se purane users ko auto Update screen
- `"expire_date": "2026-12-31"` → us date ke baad auto Expired screen (`"2026-12-31 20:00"` exact time bhi chalega)
- `"expire_message"` → expired screen ka text
- `"description"`, `"title"`, `"telegram_link"`, `"update_link"` → kabhi bhi badlo
