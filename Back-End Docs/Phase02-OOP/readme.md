<div dir="rtl" align="center">

به نام خدا

</div>

<div dir="rtl" align="right">

# شیءگرایی در زبان PHP

یکی از پرطرفدارترین سبک‌های برنامه نویسی، برنامه نویسی شیءگرا می‌باشد که در این سبک برنامه نویسی می‌توان اطلاعات و کدها را در قالب اشیاء دسته ‌بندی کرد.

این سبک برنامه نویسی در نسخه‌ی سوم زبان PHP در دسترس توسعه دهندگان قرار گرفت و در نسخه‌های چهارم و پنجم به امکانات و ابزار شیءگرایی افزوده شد. امروز فریمورک‌های پرطرفدار PHP عموما مبتنی بر شیءگرایی هستند و به همین دلیل در این بخش به موضوع شیءگرایی در زبان PHP می‌پردازیم.

برای مطالعه درباره‌ی شیءگرایی در زبان PHP به این [لینک](https://www.w3schools.com/php/php_oop_what_is.asp) مراجعه کنید.
همچنین پیشنهاد می‌شود که این [ویدئوها](https://drive.google.com/file/d/1UGV0o0lQg3vb4d1poGgC8C_joxRzcVAm/view?usp=sharing) را حتما مشاهده کنید.

## پروژه

همان گونه که در فاز اول توضیح داده شد یک چند جمله ای شامل چندین تک جمله ای است. البته چندجمله ای ها می توانند بر خلاف فاز اول که از درجه یک بودند از درجه دلخواه باشند. به عنوان مثال، f(x)=2x^5-3x^3-x+1 یک چند جمله ای از درجه پنج است چرا که بزرگترین توان آن پنج است. البته چندجمله ای ها همیشه مانند این مثال ساده و مرتب نیستند. به عنوان مثال، g(x)=3x^2-4x+5.2x^2+4x-8x^7-3 نیز یک چندجمله ای است که وقتی آن را ساده کنیم به صورت g(x)=8.2x^2-8x^7-3 ساده می شود و وقتی جملات آن را مرتب کنیم به g(x)=-8x^7+8.2x^2-3 می رسیم.

در این پروژه، از شما خواسته می شود کلاس هایی برای کار با تک جمله ای ها و چندجمله ای ها تعریف کنید. 

کلاس تک جمله ای حداقل شامل متدهای زیر است:
-  متد value که مقدار x را به عنوان پارامتر گرفته و مقدار تک جمله ای را به ازای x برگرداند. به عنوان مثال، مقدار تک جمله ای 2.5x^3 به ازای x=2 مساوی 20 است.
- متد toString برای برگرداندن تک جمله ای به صورت یک رشته
- متد derivative برای محاسبه مشتق تک جمله ای. به عنوان مثال، مشتق 2.5x^3 مساوی تک جمله ای 7.5x^2 است.

کلاس چندجمله ای نیز حداقل شامل متدهای زیر است:
-  متد value که مقدار x را به عنوان پارامتر گرفته و مقدار چندجمله ای را به ازای x برگرداند. 
- متد toString برای برگرداندن تک جمله ای به صورت یک رشته
- متد derivative برای محاسبه مشتق چندجمله ای. 
- متد simplify برای ساده سازی چندجمله
- متد sort برای مرتب سازی جملات چندجمله ای
- متدی برای جمع کردن یک تک جمله ای با یک چندجمله ای
- متدی برای تفریق کردن یک تک جمله ای از یک چندجمله ای
- متدهایی برای محاسبه حاصل جمع، تفریق و ضرب دو چندجمله ای

</div>