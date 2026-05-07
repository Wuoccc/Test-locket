# Test-locket

Locket Gold subscription unlock module for Shadowrocket, Surge, and LanceX.

## ⚠️ Disclaimer

This project is for educational purposes only. Please do not sell or redistribute these scripts to others.

## 📁 Files

| File | Description |
|------|-------------|
| `Locket_Wuoccc.js` | Main script to unlock Locket Gold subscription |
| `deleteHeader.js` | Script to delete RevenueCat ETag header |
| `Locket_Wuoccc.sgmodule` | Shadowrocket/Surge/LanceX module configuration |

## 🔧 Features

- Unlocks Locket Gold subscription features
- Bypasses RevenueCat subscription verification
- Compatible with Shadowrocket, Surge, and LanceX

## 📋 Module Configuration

The `.sgmodule` file includes:

### Script Rules
- **revenuecat**: HTTP response handler for RevenueCat API endpoints
- **deleteHeader**: HTTP request handler to clear X-RevenueCat-ETag header

### MITM Settings
- Hostname: `api.revenuecat.com`

## 🚀 Usage

1. Import the `Locket_Wuoccc.sgmodule` into your proxy app (Shadowrocket/Surge/LanceX)
2. Enable the module
3. Ensure MITM is enabled for `api.revenuecat.com`
4. Open Locket app and enjoy Gold features

## 📝 Version

- deleteHeader: V1.0.2

## 👤 Author

**Wuoccc**

## 🔗 Links

- Raw Script: https://raw.githubusercontent.com/Wuoccc/Test-locket/refs/heads/main/Locket_Wuoccc.js

---

*Crack by Wuoccc - Vui lòng không bán hoặc chia sẻ cho người khác!*