## استفاده از گفتار در بازی

در این اپلیکیشن می توانید با گفتن کلمات ذکر شده شخصیت بازی را کنترل کنید.

## توضیحات پروژه

این پروژه نقطه شروع بازی های جدید و زیبا در حیطه گفتاری است که دنیای بازی ها به این سمت کشیده میشه.

## عملکرد

محیط بازی با استفاده از یک ارایه مدیرت میشود که در آن 0 نشانه خالی بودن خانه در بازی ، 1 نشان دهنده موقعیت شخصیت بازی هست ، 2 نشان دهنده دیوارها ، 3 نشان دهنده صندوقچه هایی که یا تله هستند یا جایزه دارند و 4 نشان دهنده خاته اخر و اتمام مرحله میباشد. 
\n

در این پروژه شخصیت بازی را با کلمات ذکر شده در زیر میتوان کنترل کرد:
\n
top, up = به بالا یرو
\ndown =  به پایین برو
\nright = به سمت راست برو
\nleft = به سمت چپ برو
\n
در این بازی فعلا به صورت ابتدایی از سرویس speech to text در فلاتر استفاده میشود و اول با اسفاده از میکروفون صدای شخص با لحجه en_US به کلمه تبدیل میشود و در نهایت با تابع spliter , اولین حرف گفته شده را با کلمات مقایسه و در نهایت با استفاده از تابع update تغییرات را اعمال میکنیم.
