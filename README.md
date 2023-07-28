# GPT Engine 
# جی بی تی موتور 

[![GitHub Repo stars](https://img.shields.io/github/stars/Rahanesh/gpt-engin?style=social)](https://github.com/Rahanesh/gpt-engin)
[![Twitter Follow](https://img.shields.io/twitter/follow/Rahanesh?style=social)](https://T.me/Rahanesh)

## هوش مصنوعی **ChatGPT** ورژن 4 

**درخواست خود را کامل بیان کنید و بگویید چه چیزی توسط هوش مصنوعی ساخته شود .**

با کمک رابط هوش مصنوعی شرکت OPENAI می توانید درخواست خود را در قالب ساخت یک برنامه مطرح کنید ویژگی های برنامه مورد نظر را تشریح کنید و منتظر بمانید تا کدنویسی هوشمند شروع به ساختن برنامه کند.




## نحوه استفاده
نسخه **پایدار** یا **توسعه یافته** 
**stable** or **development**.

For **stable** release:

- `pip install gpt-engineer`

For **development**:

ایجاد یک محیط مجازی اجرای فرامین پایتون برای ویندوز 
- `python -m -venv ven`

- `venv\scripts\activate`

- `git clone https://github.com/Rahanesh/gpt-engin.git`
- `cd gpt-engin`
- `pip install -e .`
  - (or: `make install && source venv/bin/activate` for a venv)  برای لینوکس


**نصب در لینوکس و ویندوز**

کلید API خود را از سایت زیر دریافت کنید و مطابق دستورات زیر در ترمینال لینوکس یا ویندوز خود اجرا کنید.

[openai.com](https://platform.openai.com/login?launch)

با یک کلید OpenAI API (ترجیحا با دسترسی GPT-4) اجرا کنید:

**برای لینوکس**
- `export OPENAI_API_KEY=[your api key]`

**برای ویندوز**

- `set OPENAI_API_KEY=[your api key]`  on cmd
- `$env:OPENAI_API_KEY="[your api key]" ` on powershell




**اجرا**:

- یک پوشه خالی ایجاد کنید. اگر داخل مخزن هستید، می توانید دستور زیر را اجرا کنید:
- `cp -r projects/example/ projects/my-new-project`
- xcopy /E projects\example projects\my-new-project
- فایل "prompt" را در پوشه جدید خود قراردهید
- `gpt-engineer projects/my-new-project`
  - (Note, `gpt-engineer --help` با سویچ کمکی راهنما تمام گزینه های موجود را می بینید. به عنوان مثال --steps use_feedback به شما این امکان را می دهد کدهای یک پروژه را ویرایش و کامل تر کنید))



**نتیجه**
- فایل های ایجاد شده را در این مسیر بررسی کنید `projects/my-new-project/workspace`


To run in the browser you can simply:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/Rahanesh/gpt-engin/codespaces)


**نکته**

برای نحوه استفاده از ابزار می توانید ویدیوی مربوط به آن را در کانال یوتیوب ما که آدرس آن در انتهای این صفحه درج شده است مراجعه نمایید.

## نمونه


https://user-images.githubusercontent.com/4467025/243695075-6e362e45-4a94-4b0d-973d-393a31d92d9b.mov

## یوتیوب ما
