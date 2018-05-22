# ربات تلگرام رایگان با پایتون

با این آموزش میتونی یک ربات تلگرام رایگان به زبان پایتون راه بندازی

## پیش نیاز ها
* [ساخت ربات در بات فادر](https://t.me/BotFather)
* [ساخت حساب در پایتون انیور](https://www.pythonanywhere.com/registration/register/beginner/)
* [ساخت بش جدید در پایتون انیور ](https://www.pythonanywhere.com/user/rasoolhp/consoles/bash/new)
### نصب

اجرای کد های زیر در بش

```
virtualenv --python=python2.7 mybot
```
```
source mybot/bin/activate
```
```
pip install python-telegram-bot
```

**برنامه ربات**

```
git clone https://github.com/rasoolhp/free-telegram-bot.git
```

```
cd free-telegram-bot
```

```
nano bot.py
```
```
توکن رو جایگذاری کن و بعد ذخیره کن با کنترل+ایکس بعد ایگرگ بعد اینتر
```
```
cd ..
```
### اجرا

```
source mybot/bin/activate
```

```
python2 free-telegram-bot/bot.py
```
