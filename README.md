# Telegram Session String Generator 🔑

Generate Telegram session strings easily using this Google Colab notebook. Perfect for developers building Telegram bots or tools with Telethon!

![Demo](https://raw.githubusercontent.com/SudoR2spr/Telethon-Session-Generator/refs/heads/master/Demo-screen/Demo-screen.png)

## 📋 Prerequisites
- Google Account (to use Colab)
- Verified Telegram account
- Basic Python knowledge

## 🚀 Quick Start

### 1. Open the Colab Notebook
<p align=center><a href="https://colab.research.google.com/github/SudoR2spr/Telethon-Session-Generator
/blob/master/Telethon%20Session%20Generator/session-op.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab Link"/>
  </a></p> 


### 2. Run the Notebook
1. **Install Dependencies**  
   Run the first code cell to install Telethon:
   ```python
   !pip install telethon
   ```

2. **Enter API Credentials**  
   Get your `API_ID` and `API_HASH` from:
   [my.telegram.org](https://my.telegram.org/auth) → **API development tools**

3. **Run Session Generator**  
   Follow the prompts:
   ```python
   [?] Enter API ID: 1234567
   [?] Enter API HASH: a1b2c3d4e5f6g7h8i9j0
   [?] Phone Number (+1XXX): +1234567890
   ```

### 3. Verify Login
- You'll receive a **verification code** via Telegram
- Enter the code in Colab when prompted
- If 2FA is enabled, provide your password

### 4. Get Session String
The session string will be:
1. Printed in Colab outputs
2. Sent to your Telegram **Saved Messages**:
   ```
   ⚠️ **✔️ Your Session String:**
   💻 Developer: 𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭
   ⚠️ Warning: Never share this with anyone! 🤫

   `1AbcDEfghIJKlmnOPqrStuVWXYz0123456789abcDEFghiJKLmnoPQRStuvWXYZ=`
   ```

## ⚠️ Security Tips
- 🔒 **Never share** your session string
- 🗑️ Delete old/unused sessions
- 🤖 Only use with trusted bots
- 📛 Revoke suspicious sessions via [Telegram Settings](https://my.telegram.org/sessions)

## 🆘 Support
For help:
- Join our [Telegram Group](https://t.me/Opleech_WD)
- Report issues on [GitHub](https://github.com/SudoR2spr/Telethon-Session-Generator/issues)
- Contact Developer: `@Farooq_is_king`

---

