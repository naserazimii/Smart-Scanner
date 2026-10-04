عنوان پروژه: Smart Scanner (اسکنر هوشمند اسناد)

این نرم‌افزار یک برنامه سبک، سریع و کاملاً بومی برای سیستم‌عامل ویندوز است که با استفاده از پایتون و رابط رابط کاربری (WIA) توسعه یافته است. این برنامه دارای یک رابط کاربری گرافیکی مدرن و کاربرپسند (با الهام از ویندوز ۱۱) بوده و به کاربران اجازه می‌دهد اسناد خود را با بالاترین کیفیت و کنترل دقیق اسکن کنند.

یکی از بزرگترین مشکلات درایورهای ویندوز این است که در کیفیت‌های بالا (مثل 300 یا 600 DPI)، درایور به دلیل محدودیت بافر به صورت خودکار ابعاد صفحه را برش می‌زند (مثلاً A4 را به A5 تبدیل می‌کند). این نرم‌افزار با داشتن یک الگوریتم "هوشمند ضد برش" این مشکل را به طور کامل حل کرده است.

ویژگی‌های کلیدی (Key Features):

شناسایی خودکار سخت‌افزار: جستجو و اتصال خودکار به تمام اسکنرهای متصل به سیستم از طریق درایورهای WIA.

سیستم هوشمند ضد برش (Anti-Crop): محاسبه خودکار محدودیت‌های سخت‌افزاری و تطبیق امنِ کیفیت (DPI) برای جلوگیری از کوچک شدن یا برش خوردن اسناد در رزولوشن‌های بالا.

پشتیبانی از ابعاد استاندارد: اسکن دقیق برگه در ابعاد A3 ،A4 و A5.

حالت‌های رنگی متنوع: امکان انتخاب بین حالت‌های تمام‌رنگی (Color)، طیف خاکستری (Grayscale) و سیاه و سفید (Black & White).

خروجی چندگانه: ذخیره مستقیم تصاویر به صورت فایل JPG یا تبدیل خودکار و سریع به اسناد PDF.

نام‌گذاری خودکار (Auto-Naming): تولید نام فایل‌های کاملاً منحصر‌به‌فرد بر اساس تاریخ و ساعت سیستم برای جلوگیری از پاک شدن فایل‌های قبلی.

کاملاً پرتابل و مستقل: خروجی در قالب یک فایل اجرایی (.exe) که در سیستم‌های دیگر نیازی به نصب پایتون یا پیش‌نیازهای اضافه ندارد.

🇬🇧 English Description (For GitHub README)
Project Title: Smart Scanner Application

Smart Scanner is a lightweight, fast, and native Windows application built with Python and the Windows Image Acquisition (WIA) API. It features a modern, clean, and user-friendly GUI (inspired by Windows 11) designed to give users precise control over their document scanning workflows.

A common issue with standard Windows scanner drivers is that scanning at high resolutions (e.g., 300 or 600 DPI) often causes the driver to hit hardware buffer limits, resulting in unwanted document cropping (e.g., shrinking an A4 page to A5). This software features a custom "Smart Anti-Crop Algorithm" that completely resolves this issue.

Key Features:

Auto Hardware Detection: Seamlessly detects and connects to available scanners using WIA drivers.

Smart Anti-Crop System: Automatically calculates hardware buffer limits and safely adjusts the DPI to maintain full document dimensions, preventing unwanted cropping at high resolutions.

Standard Page Sizes: Precise extent calculations for standard A3, A4, and A5 document sizes.

Multiple Color Modes: Choose between full Color, Grayscale, and pure Black & White scanning intents.

Multi-Format Export: Directly save scanned documents as JPG images or automatically convert them into PDF documents.

Timestamp Auto-Naming: Generates unique filenames based on the exact system date and time to prevent accidental file overwriting.

Standalone Executable: Packaged as a single .exe file that runs smoothly on Windows without requiring a Python environment or additional dependencies.
