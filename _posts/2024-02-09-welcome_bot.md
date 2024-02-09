---
categories: [Examples]
tags: []
---

## بات خوش آمد گویی

**این بات را در یک گروه عضو کنید تا به اعضای جدید پیام خوش آمد گویی ارسال کند**

```python
from balethon import Client
from balethon.conditions import new_chat_members

bot = Client("TOKEN")


@bot.on_message(new_chat_members)
async def welcome_new_chat_members(message):
    members = [member.full_name for member in message.new_chat_members]
    await message.reply(
        f"Hello {', '.join(members)}, welcome to {message.chat.title}!"
    )


bot.run()
```