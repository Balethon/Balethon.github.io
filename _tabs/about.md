---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
img_path: /assets/img/
---

<p align="center">
  <img src="/assets/img/logo.png" width="200" alt="Balethon">
</p>

<h1 align="right" dir="rtl">بله</h1>

<p align="right" dir="rtl">پیام‌رسان بانکی <a href="https://www.bale.ai/">بله</a>، شبکۀ اجتماعی‌مالی بانک ملّی ایران است که هم‌زمان امکان گفتگو و پرداخت را برای شما فراهم می‌کند</p>

<h1 align="right" dir="rtl">بلتون</h1>

<p align="right" dir="rtl">بلتون یک کتابخانه برای ساختن بات در پیام‌رسان <a href="https://www.bale.ai/">بله</a> با زبان برنامه نویسی پایتون است</p>

<p align="right" dir="rtl"><br/></p>

<h2 align="right" dir="rtl">نمونه ساده</h2>

<p align="right" dir="rtl">کد یک بات که هر پیامی به آن بدهید، با متن <code>Hello</code> جواب میدهد</p>

```python
from balethon import Client

bot = Client("TOKEN")  # Replace "TOKEN" with your actual token here


@bot.on_message()
async def greet(message):
    await message.reply("Hello")


bot.run()
```

<blockquote dir="rtl">
<p>باید <code>TOKEN</code> را با توکنی که <a href="https://ble.ir/botfather">BotFather</a> در پیام‌رسان <a href="https://www.bale.ai/">بله</a> به شما میدهد عوض کنید</p>
</blockquote>

<p align="right" dir="rtl"><br/></p>

<h2 align="right" dir="rtl">امکانات کلیدی</h2>

<dl dir="rtl">
<dt><a href="https://balethon.ir/posts/balethon-is-easy">آسان</a></dt>
<dd>رابط کاربری مختصر و سطح بالا</dd>
<dt><a href="https://balethon.ir/posts/balethon-is-fast">سریع</a></dt>
<dd>بهینه و دارای پشتیبانی از برنامه نویسی Asynchronous</dd>
<dt><a href="https://balethon.ir/posts/balethon-is-documented">مستند سازی شده</a></dt>
<dd>در مستندات به طور جامع و عمیق به آموزش بلتون پرداخته شده</dd>
<dt><a href="https://balethon.ir/posts/balethon-has-community">کامیونیتی</a></dt>
<dd>انجمن مخصوص پرسش و پاسخ فعال و دوستانه</dd>
<dt><a href="https://balethon.ir/posts/balethon-has-design-options">معماری</a></dt>
<dd>پشتیبانی از معماری های تابع گرا علاوه بر شیء گرا</dd>
<dt><a href="https://balethon.ir/posts/balethon-is-powerful">قدرتمند</a></dt>
<dd>API پیام‌رسان بله را پوشش میدهد و ابزارهای مفیدی برای ساده‌سازی کار شما دارد</dd>
<dt><a href="https://balethon.ir/posts/balethon-is-flexible">انعطاف‌پذیر</a></dt>
<dd>غیرقابل منسوخ شدن و آماده برای پاسخ های غیرمنتظره از سمت وب سرویس پیام‌رسان بله</dd>
<dt><a href="https://balethon.ir/posts/balethon-is-intuitive">شهودی</a></dt>
<dd>دارای type-hint و پشتیبانی عالی از ادیتورها</dd>
<dt><a href="https://balethon.ir/posts/balethon-is-extensible">توسعه پذیر</a></dt>
<dd>همه سیستم های بلتون به سادگی قابل توسعه هستند</dd>
</dl>

<p align="right" dir="rtl"><br/></p>

<h2 align="right" dir="rtl">لینک ها</h2>

<ul dir="rtl">
<li><a href="https://github.com/Balethon/Balethon">صفحه گیتهاب</a></li>
<li><a href="https://pypi.org/project/Balethon">صفحه پایپی</a></li>
<li><a href="https://ble.ir/balethon">کانال اخبار در بله</a></li>
<li><a href="https://ble.ir/join/AKFu3vHBm1">گروه چت در بله</a></li>
</ul>

<br>

<p align="center" dir="rtl">پست بعدی: <a href="https://balethon.ir/posts/installing">Installing</a></p>
