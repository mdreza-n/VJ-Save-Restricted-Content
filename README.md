# Save Restricted Bot

*A Telegram Bot, Which can send you restricted content by it's post link*

---

## Variables

- `HASH` Your API Hash from my.telegram.org
- `ID` Your API ID from my.telegram.org
- `TOKEN` Your bot token from [BotFather](https://telegram.me/BotFather)
- `STRING` Your pyrogram session string, you can get it from [VJ String Session Generator Bot](https://telegram.me/VJStringSessionBot)

---
<details><summary><b>Deploy To VPS</summary>


```
git clone [https://github.com/VJBots/VJ-Filter-Bot](https://github.com/mdreza-n/Save-Restricted-Content.git)
```

Install Packages

```
pip3 install -U -r requirements.txt
```

Edit info.py with variables as given below then run bot

```
python3 bot.py
```

</b>
</details>

# Usage

__FOR PUBLIC CHATS__

_just send post/s link_


__FOR PRIVATE CHATS__

_first send invite link of the chat (unnecessary if the account of string session already member of the chat)
then send post/s link_


__FOR BOT CHATS__

_send link with '/b/', bot's username and message id, you might want to install some unofficial client to get the id like below_

```
https://t.me/b/botusername/4321
```

__MULTI POSTS__

_send public/private posts link as explained above with formate "from - to" to send multiple messages like below_


```
https://t.me/xxxx/1001-1010

https://t.me/c/xxxx/101 - 120
```

_note that space in between doesn't matter_

### Credits

- [BipinKrish](https://github.com/bipinkrish)
- [Tech VJ](https://telegram.dog/Kingvj01)
