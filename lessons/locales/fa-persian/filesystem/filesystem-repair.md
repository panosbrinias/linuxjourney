# تعمیر فایل‌سیستم

## محتویات درس

بعضی وقت‌ها فایل‌سیستم‌ها در بهترین شرایط و وضعیت قرار ندارند. مثلاً وقتی سیستم یک دفعه‌ای خاموش می‌شود، ممکن است که اطلاعاتمان خراب شود. البته این وظیفه‌ی سیستم است که ما را به وضعیت درست هدایت کند و سیستمی که کار می‌کند را به ما تحویل دهد. به عبارتی شرایط را برای شروع به کار سیستم، بعد از، از دست دادن اطلاعات مهیا کند. هرچند ما می‌توانیم خودمان نیز به صورت دستی همین کار را انجام دهیم.

فرمانِ بررسی فایل‌سیستم یا **fsck** سلامت و انسجام یک فایل‌سیستم را آزمایش و حتی می‌تواند تلاش برای رفع مشکل کند. معمولاً وقتی که یک دیسک را راه‌اندازی می‌کنید، fsck قبل از اینکه دیسک شما سوار شود، از خوب بودن اوضاع اطمینان حاصل پیدا می‌کند. بعضی وقت‌ها اوضاع دیسک دیگر به حدی خراب است که شما مجبور به انجام دستی این کار می‌شوید. در ضمن بایستی برای این کار از طریق یک دیسک نجات و یا به هر نحوی به فایل‌سیستم، بدون نیاز به سوار کردن آن، دسترسی داشته باشید. به همین خاطر اگر قرار است که فایل‌سیستمی که حکم دایرکتوری خانه یا روت را برای شما دارد، تعمیر کنید، لازم است از سیستم‌عامل دیگری استفاده کنید چرا که در سیستم‌عامل خود به هر حال مجبور به سوار کردن این فایل‌سیستم‌ها خواهید بود.

```$ sudo fsck /dev/sda```

## تمرین

نگاهی بر manpage فرمان fsck بیندازید. چه کارهای دیگری می‌توانید با آن انجام دهید؟

## سؤال آزمون

از چه دستوری برای بررسی سلامت فایل‌سیستم استفاده می‌کنید؟

## پاسخ آزمون

fsck
