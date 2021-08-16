<div dir=rtl align="center">
به نام خدا
</div>
<div dir="rtl" align='right'>
  

# آشنایی با زبان دارت

## دارت چیست؟

دارت (به انگلیسی: Dart) زبان برنامه‌نویسی‌ است که توسط گوگل توسعه داده می‌شود. هدف دارت جایگزین کردن جاوااسکریپت که زبان داخلی مرورگرهای وب است می‌باشد. دارت راه حلی برای مشکلات موجود در جاوا اسکریپت (به‌طور مثال مشکل حافظه) می‌باشد که کارایی بهتر، قابلیت استفاده ساده‌تر برای پروژه‌های بزرگ و امنیت بیشتری را فراهم می‌کند. گوگل همچنین بسیار تلاش دارد تا دارت را پیچیده تر بسازد و ویژگی‌ها و قابلیت‌های فراوانی به آن ببخشد.

دارت زبانی برپایه کلاس، وراثت یگانه و شی گرایی است که گرامر آن شبیه زبان C بوده و دارای Interface، کلاسهای انتزاعی( Abstract Classes ) و نوع‌دهی اختیاری( Optional typing ) می‌باشد. این زبان توسط لارس بک( Lars Bak ) و کسپر لاند( Kasper Lund ) پایه‌گذاری شده‌است.

### کامپایل به جاوا اسکریپت

dartc اولین کامپایلری بود که توانایی تولید جاوا اسکریپت از روی کد دارت را داشت، ولی هم‌اکنون از رده خارج شده‌است. Frog دومین کامپایلر دارت به جاوا اسکریپت بود که به زبان دارت نوشته شد، ولی هرگز نتوانست مفاهیم کلی زبان دارت را پیاده‌سازی نماید، البته بعد از آن کامپایلر جدیدی به نام dart2js به زبان دارت نوشته شد و هم‌اکنون کامپایلری است که تمام ویژگی‌ها و مفاهیم این زبان را پشتیبانی می‌نماید.

## نصب و راه‌اندازی

برای نوشتن کد به زبان دارت مانند سایر زبان‌های برنامه نویسی به یک محیط توسعه( IDE ) نیاز دارید که IDEهای پیشنهادی  [VSCode](https://code.visualstudio.com/) و [IntelliJ IDEA](https://www.jetbrains.com/idea/download) می‌باشند. در کنار IDE برای اجرای کدهای زبان دارت به بسته توسعه نرم افزار( SDK ) این زبان نیز نیاز دارید. 

برای دیدن مشخصات  مورد نیاز سیستم به [لینک](https://dart.dev/get-dart#system-requirements) و 
برای آشنایی با نحوه نصب SDK و ایجاد پروژه Hello World  به [لینک](https://dart.dev/tutorials/server/get-started) مراجعه کنید، همچنین برای اجرا و تست کدهای زبان دارت بدون نصب SDK و با استفاده از مرورگر خود  میتوانید از ابزار [Dartpad](https://dart.dev/tools/dartpad) استفاده کنید.

### راهنمای شروع کار با IntelliJ IDEA

برای مشاهده راهنما به [لینک](https://dart.dev/tools/jetbrains-plugin#configuring-dart-support) مراجعه کنید.

### راهنمای شروع کار با VSCode 

![vscode1](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode1.png)

  
01. بر روی view کلیک کنید.
02. گزینه‌ی Extensions را انتخاب کنید( از میانبر نمایش داده شده نیز میتوانید استفاده کنید ).
  

![vscode2](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode2.png)

03. عبارت Dart را سرچ کنید.
04. افزونه‌ زبان دارت را انتخاب کنید.
05. افزونه را نصب کنید.
  
  

![vscode3](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode3.png)

بر روی view کلیک کنید و  Command Palette را انتخاب کنید یا کلید ترکیبی Ctrl+Shift+P را فشار دهید.

06. Dart: New Project را تایپ کرده و انتخاب کنید.

![vscode4](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode4.png)

  
07. template مناسب برای پروژه جدید را انتخاب کنید( برای شروع بهتر است Console Application را انتخاب کنید )

![vscode5](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode5.png)

  
08. مسیر ذخیره پروژه را تعیین کنید.
09. با کلیک بر روی دکمه مسیر را انتخاب کنید.

![vscode6](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode6.png)

10. برای پروژه نام انتخاب کنید.

![vscode7](https://github.com/MARS-JSU/Internship-Documents/blob/Mobile/Mobile%20Docs/Phase01-Dart/vscode7.png)

  
11. فایل با نام پروژه در پوشه ی bin را باز کنید. 
12. با کلیک بر گزینه Debug یا Run  یا با استفاده از کلید F5 پروژه را اجرا کنید. 

## شروع به کار با دارت

برای یادگیری زبان دارت پیشنهاد می‌شود که به این [لینک](https://dart.dev/guides/language/language-tour) مراجعه کنید و همچنین تا جای ممکن نمونه‌ کدهای درون متن آموزش را بازنویسی کرده و اجرا کنید.

### Sound Null Safety

برای آشنایی با `Sound Null Safety` به [لینک](https://dart.dev/null-safety) مراجعه کنید.

 پس از ورژن `Dart 2.12` ، پروژه‌های دارت به صورت پیش‌فرض با   `Sound Null Safety` ساخته میشوند. برای اجرا و توسعه پروژه‌های دارت **بدون استفاده** از `Sound Null Safety` میتوانید به [لینک](https://dart.dev/null-safety/unsound-null-safety#migrating-by-hand) مراجعه کنید.

## مباحث تکمیلی زبان دارت

 برای یادگیری بیشتر مباحث زیر را نیز مطالعه کنید.

* [Effective Dart](https://dart.dev/guides/language/effective-dart)( برای کدنویسی بهتر )
* [Packages](https://dart.dev/guides/packages)

</div>
