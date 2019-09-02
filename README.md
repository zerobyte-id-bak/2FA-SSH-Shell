# 2FA-SSH-Shell
Two-Factor Authentication with Telegram Bot for SSH / Shell Login

# Setup

### Create Your Own Bot:
Chat `@BotFather` with `/newbot`

### Setup Bot for OTP Sender
- Open your API: `https://api.telegram.org/bot[HTTP_API_KEY]/getUpdates`
- Chat your Telegram Bot
- Copy your `Chat ID`
![BOT Chat ID](https://raw.githubusercontent.com/zerobyte-id/2FA-SSH-Shell/master/Screenshot/BOT-API-GetUpdates.png)
- Download `shell2FA` source
- Change configuration `API KEY` & `Chat ID` on "shell2FA" source
- Move `shell2FA` to `/bin/` (`mv shell2FA /bin/`)
- `chmod +x /bin/shell2FA
- Change shell in `/etc/passwd` => Example `/bin/bash` to `/bin/shell2FA`
![/etc/passwd](https://raw.githubusercontent.com/zerobyte-id/2FA-SSH-Shell/master/Screenshot/etc-passwd.png)
