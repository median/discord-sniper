
# **GhaphSniper - Discord Username Sniper**
![](https://img.shields.io/github/downloads/median/discord-sniper/total?label=Downloads)
![](https://img.shields.io/github/stars/median/discord-sniper)

The fastest and easiest to use Discord sniper, all for free. Might make this open source in the future, but for now it's closed source.

[Contact me](https://t.me/charset)

## **Features**
- Many concurrent claim tokens, rotating in order to avoid any rate limits
- Can snipe thousands of usernames concurrently, but 1-20 is recommended (read disclaimer below for more info)
- Many concurrent captcha accounts with automatic balance/key checking & handling
- Proxy support if you want to claim at the fastest speed
- Customizable thread count
- Discord webhook logs (see below for pictures)

## **Usage**
**1)** Download the latest windows/linux build [here](https://github.com/median/discord-sniper/releases/latest) and put it in it's own folder

**2)** Create 3 files: tokens.txt, proxies.txt, usernames.txt. Each item in each text file is seperated by a new line. The token format must be `email:pass:token` or `pass:token`. The proxy format must be `user:pass@ip:port` or `ip:port`.

**3)** Start the program, it will create your config.json for you.

**4)** Fill out the config and re run the program and it will automatically start claiming. If you're getting config errors on startup, paste it into [here](https://jsonlint.com/) so it can tell you what's wrong with your config.

Once a username is claimed, it will appear in `claimed.txt` in the following format:
```username:email:pass:token```

## **Supported captcha services**
- [CapSolver](https://ghaph.com/r/capsolver) (Recommended if you are using proxies)
- [CapMonster](https://capmonster.cloud) (Recommended)
- [AntiCaptcha](https://ghaph.com/r/anticaptcha)
- [2captcha/ruCaptcha](https://2captcha.com)
- [Anycaptcha](https://anycaptcha.com/)

## **Images**
Will put some here soon

### **DISCLAIMER**
This is not an autoclaimer, this tool should only be used for swapping usernames or when you know a username will drop soon (like when a username is just recently changed) because this will eat up your captcha balance.