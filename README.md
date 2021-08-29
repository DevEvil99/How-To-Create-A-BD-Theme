<div align="center">
 <h1>How to create a Discord theme</h1> <br>
 <h1>چطوری یک تم دیسکورد بسازیم</h1> <br>

Languages : <br>
 <a href="#eng">English</a><br>
[Persian/Farsi](https://github.com/DevEvil99/How-To-Create-A-BD-Theme#fa) 
</div>
<br>
<br>
<br>
<br>
<section id="fa">
<div dir="auto">
<img src="https://cdn.discordapp.com/attachments/468141324906921984/881258359557345380/header.png" /> <br>
<div align="center">

# یک داکیومنت ساخت تم دیسکورد برای شما 😀 
آموزش ساخت تم برای دیسکورد به زبان فارسی <br>
قبل از اینکه شروع کنیم باید بگم که من چیز هایی که خودم میدونم رو به شما دارم یاد میدم و ادعایی ندارم 😃❤ <br>
من تو نوشتن فارسی ضعیفم پس اگه غلط املایی یا چیزی پیدا کردید تعجب نکنید ☺😅
</div>

# پیش نیاز ها 📃
* [بتر دیسکورد | BetterDiscord](https://betterdiscord.app/)
* [یک نرم افزار ادیت کد | پیشنهاد من : Visual Studio Code ](https://code.visualstudio.com/download) <br>
بتر دیسکورد چیه ؟ بتر دیسکورد (بی دی) به طور مختصر یک کلاینت برای دیسکورد که بما اجازه میده بتونیم روی دیسکورد تم و پلاگاین نصب کنیم <br>
# آموزش نصب بتر دیسکورد ❗


https://user-images.githubusercontent.com/73029696/131230139-ac3a1b8d-b30c-482a-a32c-db195bdabb0b.mp4

# قبل از اینکه شروع کنیم ❗
برای اینکه ما تم بسازیم باید به المنت های دیسکورد استایل بدیم حالا چجوری این المنت ها رو پیدا کنیم 🤔<br>
برای پیدا کردن المنت ها باید دکمه های زیر را بزنیم <br>
* Windows : ``Ctrl+Shift+I`` <br>  
* Mac : ``⌥+⌘+I``  <br>
بعد از زدن این دکمه ها صفحه ی inspector برای شما باز میشه

![Untitled](https://user-images.githubusercontent.com/73029696/131230398-63dc2325-552a-409e-b320-fe8bdbfa4a66.png)

وقتی این صفحه باز شد دکمه ی ``Ctrl+Shift+C`` رو باید بزنید تا بتونید روی المنت ها کلیک کنید



https://user-images.githubusercontent.com/73029696/131230597-dcd22461-15a7-461e-8245-a90ca156124b.mp4

همینطور که دیدید الان ما کلاس آیکون های روی چت اینپت رو بدست آوردیم <br>
* icon-3D60ES <br>
و همینجوری با کلیک کردن روی المنت های مختلف میتونیم کلاس هاشون رو پیدا کنیم <br>

# ساخت فایل تم 📃
برای ساخت فایل تم باید به پوشه ی تم بی دی بریم، دو تا را وجود داره
1. باز کردن از توی دیسکورد <br><br>
![Untitled](https://user-images.githubusercontent.com/73029696/131230809-7aaa9425-a705-407e-adde-1a428fe101ef.png)
![Untitled2](https://user-images.githubusercontent.com/73029696/131230815-88dd3c77-ab40-4e48-bccf-03ceaa59a5b1.png)
2. معمولی
``C:\Users\username\AppData\Roaming\BetterDiscord\themes``
بعد از وارد شدن به پوشه ی تم باید فایل تم رو بسازیم <br>
توجه : فایل تم شما باید ``.theme`` رو داشته باشه <br>
مثال : ``Amozesh.theme.css`` <br>
برای ساختن تم میتونید از ``css`` و ``sass`` استفاده کنید <br>

# کد نویسی 💻
خب الان که همچی رو یاد گرفتیم و فایل رو ساختیم وارد فایل میشیم <br><br>
شما باید باید باید در اول فایل خودتون کد زیر رو قرار بدید وگرنه تم کار نمیکنه <br>
```css
/**
  * @name Dark+ اسم تم
  * @author DevEvil#8745 اسم سازنده
  * @version Dark+1 ورژن تم
  * @description Highly customized dark and purple theme for Discord توضیحات
  * @authorId 468132563714703390 آیدی دیسکورد سازنده
  * @authorLink https://devevil.xyz لینک سازنده
  * @source https://github.com/DevEvil99/DarkPlus-Discord-Theme لینک سورس کد
  * @website https://devevil.xyz وبسایت
  * @invite jsQ9UP7kCA لینک ساپورت سرور
*/
```
ضروری 
* @name
* @version
* @description <br>
حالا که فایل رو آماده کردیم اولین کد خودمون رو مینویسیم <br>
المنت موردنظر رو کپی میکنیم و بهش استایل میدیم <br>
![Untitled](https://user-images.githubusercontent.com/73029696/131231225-a594705f-e2ae-4291-b02e-122a086f0b4e.png)

نتیجه <br> 
![Untitled2](https://user-images.githubusercontent.com/73029696/131231231-e5f420bf-dd1f-4e5f-acc9-406d0a1a2522.png)

به همین راحتی تم خودمون رو ساختیم 😀 <br>

خیلی کار میتونین با دیسکورد بکنید بستگی به سلیقتون داره اگه سی اس اس رو بلد باشید میتونید خیلی کار ها مثل عوض کردن آیکون ها ، متحرک کردن المنت ها ، عوض کردن جای المنت و ... انجام بدید <br>

مرسی که تا اینجا منو دنبال کردید 😀❤ <br>

اگه مشکلی ، سوالی یا کمکی خواستید میتونید از راه های زیر با من در ارتباط باشید <br>
* [Email](https://devevil.xyz/contact)
* Discord : DevEvil#8745
* [Discord Server](https://discord.gg/jsQ9UP7kCA) 

دانلود تم من : [اینجا کلیک کنید](https://betterdiscord.app/theme?id=412) <br>


❤
</section>

![logo2](https://cdn.discordapp.com/attachments/468141324906921984/881522240896790569/header2.png)

<section id="eng">
<div dir="auto">
<div align="center">
<---------------------------------------------English---------------------------------------------> <br>
A document to create a discord theme 😀 <br>
Learn how to create a theme for Discord <br>
Before we begin, I must say that I am teaching you what I know and I have no claim 😃❤
</div>

# Prerequisites 📃
* [BetterDiscord](https://betterdiscord.app/)
* [Code editor | My suggestion : Visual Studio Code](https://code.visualstudio.com/download) <br>
What is Better Discord? BetterDiscord (BD) In short, a client for Discord that allows us to install themes and plugins on Discord

# BetterDiscord installation tutorial ❗

https://user-images.githubusercontent.com/73029696/131230139-ac3a1b8d-b30c-482a-a32c-db195bdabb0b.mp4

# Before we start ❗
In order for us to create a theme, we have to style the discord elements. Now, how do we find these elements 🤔 <br>
To find the elements, we have to hold the buttons below
* Windows : ``Ctrl+Shift+I``
* Mac : ``⌥+⌘+I`` <br>
After holding these buttons, the inspector page will open for you

![Untitled](https://user-images.githubusercontent.com/73029696/131230398-63dc2325-552a-409e-b320-fe8bdbfa4a66.png)

When this page opens, you have to press ``Ctrl+Shift+C`` to be able to click on the elements 

https://user-images.githubusercontent.com/73029696/131230597-dcd22461-15a7-461e-8245-a90ca156124b.mp4

As you can see, we have now got a class of icons on the chat input
* icon-3D60ES <br>
And so by clicking on different elements we can find their classes

# Creating theme file 📃
To create a theme file, we need to go to the BD theme folder, there are two ways
1. Open it from Discord <br><br>
![Untitled](https://user-images.githubusercontent.com/73029696/131230809-7aaa9425-a705-407e-adde-1a428fe101ef.png)
![Untitled2](https://user-images.githubusercontent.com/73029696/131230815-88dd3c77-ab40-4e48-bccf-03ceaa59a5b1.png) <br>
2. Normal ``C:\Users\username\AppData\Roaming\BetterDiscord\themes`` <br>
After entering the theme folder, we need to create the theme file <br>
Note : Your theme file must have ``.theme`` <br>
Example : ``Amozesh.theme.css`` <br>
You can use ``css`` and ``sass`` to create the theme

# Coding 💻
Well, now that we have learned everything and created the file, we will enter the file <br>
You must put the following code in the beginning of your file code, otherwise the theme will not work <br>
```css
/**
  * @name Dark+ Theme Name
  * @author DevEvil#8745 Theme Author
  * @version Dark+1 Theme Version
  * @description Highly customized dark and purple theme for Discord  Theme Description
  * @authorId 468132563714703390 Theme Author Discord ID
  * @authorLink https://devevil.xyz Theme Author Link
  * @source https://github.com/DevEvil99/DarkPlus-Discord-Theme Source Code Link
  * @website https://devevil.xyz Website
  * @invite jsQ9UP7kCA Support Server
*/
```
Necessary
* @name
* @version
* @description <br>

Now we write our first code <br>
We copy the element and style it <br>
![Untitled](https://user-images.githubusercontent.com/73029696/131231225-a594705f-e2ae-4291-b02e-122a086f0b4e.png) <br>

Result <br> 
![Untitled2](https://user-images.githubusercontent.com/73029696/131231231-e5f420bf-dd1f-4e5f-acc9-406d0a1a2522.png) <br>

We made our own theme so easily 😀 <br>
There is a lot you can do with Discord, it depends on your taste. If you know CSS, you can do a lot of things such as changing icons, giving animation to the elements, changing the location of elements, and so on <br>
Thank you for following me so far 😀❤ <br>

If you have a problem, question or need help, you can contact me in the following ways
* [Email](https://devevil.xyz/contact)
* Discord : DevEvil#8745
* [Discord Server](https://discord.gg/jsQ9UP7kCA) <br><br>

Download my theme : [Click here](https://betterdiscord.app/theme?id=412) <br>

❤


 
</section>
