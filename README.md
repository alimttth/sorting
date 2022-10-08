# sorting

گوریتم مرتب‌سازی، در دانش رایانه و ریاضی، الگوریتمی است که فهرستی از داده‌ها را به ترتیبی مشخص می‌چیند.

پرکاربردترین ترتیب‌ها، ترتیب‌های عددی و واژه‌نامه‌ای هستند. مرتب‌سازی کارا در بهینه‌سازی الگوریتم‌هایی که به فهرست‌های مرتب شده نیاز دارند (مثل جستجو و ترکیب)، اهمیت زیادی دارد.

از آغاز علم رایانه مسائل مرتب‌سازی بررسی‌های فراوانی را متوجه خود ساختند؛ شاید به این علت که در عین ساده بودن، حل آن به صورت کارا پیچیده است. برای نمونه مرتب‌سازی حبابی در سال ۱۹۵۶ به وجود آمد. در حالی که بسیاری این را یک مسئلهٔ حل شده می‌پندارند، الگوریتم کارآمد جدیدی همچنان ابداع می‌شوند (مثلاً مرتب‌سازی کتابخانه‌ای در سال ۲۰۰۴ مطرح شد).

مبحث مرتب‌سازی در کلاس‌های معرفی علم رایانه بسیار پرکاربرد است؛ مبحثی که در آن وجود الگوریتم‌های فراوان به آشنایی با ایده‌های کلی و مراحل طراحی الگوریتم‌های گوناگون کمک می‌کند؛ مانند تحلیل الگوریتم، داده‌ساختارها، الگوریتم‌های تصادفی، تحلیل بدترین و بهترین حالت و حالت میانگین، هزینهٔ زمان و حافظه، و حد پایین.


نام	میانگین	بدترین	حافظه	پایداری	روش	نکات اضافه
مرتب‌سازی ادغامی	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}n}{\displaystyle {\mathcal {}}n}	بله	ادغام	
مرتب‌سازی ادغامی درجا	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	بستگی دارد	ادغام	نمونه پیاده‌سازی اینجا: [۳]؛ می‌تواند به عنوان یک مرتب‌سازی پایدار پیاده‌سازی شود: [۴]
مرتب‌سازی انتخابی	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	بستگی دارد	انتخاب	پایدار بودن آن به پیاده‌سازی بستگی دارد
مرتب‌سازی حبابی	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	بله	تعویض	کد کوتاه
مرتب‌سازی حبابی دوسویه	—	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	بله	تعویض	
مرتب‌سازی درجی	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	بله	درج	حالت میانگین همچنین {\displaystyle {\mathcal {O}}\left({n+d}\right)}{\displaystyle {\mathcal {O}}\left({n+d}\right)} می‌باشد که d تعداد درج‌هاست.
مرتب‌سازی درختی	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}n}{\displaystyle {\mathcal {}}n}	بله	درج	باید از یک درخت دودویی جستجوگر خودمتوازن استفاده شود
مرتب‌سازی درونگرا	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}	{\displaystyle {\mathcal {O}}\left({\log n}\right)}{\displaystyle {\mathcal {O}}\left({\log n}\right)}	خیر	مرکب	استفاده شده در پیاده‌سازی‌های SGI STL
مرتب‌سازی رشته‌ای	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}	{\displaystyle {\mathcal {O}}\left({n^{2}}\right)}{\displaystyle {\mathcal {O}}\left({n^{2}}\right)}	{\displaystyle {\mathcal {O}}\left(n\right)}{\displaystyle {\mathcal {O}}\left(n\right)}	بله	انتخاب	
مرتب‌سازی روان	—	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	خیر	انتخاب	
مرتب‌سازی سریع	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}	{\displaystyle {\mathcal {O}}\left(n^{2}\right)}{\displaystyle {\mathcal {O}}\left(n^{2}\right)}	{\displaystyle {\mathcal {O}}\left({\log n}\right)}{\displaystyle {\mathcal {O}}\left({\log n}\right)}	بستگی دارد	تقسیم‌بندی	با توجه به شیوه‌ای که محور عمل می‌کند، می‌تواند به صورت پایدار پیاده‌سازی شود؛ گونهٔ دیگری از آن از حافظه {\displaystyle {\mathcal {O}}\left(n\right)}{\displaystyle {\mathcal {O}}\left(n\right)} استفاده می‌کند.
مرتب‌سازی شانه‌ای	—	—	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	خیر	تعویض	کد کوتاه
مرتب‌سازی شکیبانه	—	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}	{\displaystyle {\mathcal {O}}\left(n\right)}{\displaystyle {\mathcal {O}}\left(n\right)}	خیر	درج و انتخاب	بزرگ‌ترین زیردنباله‌های افزایشی را با {\displaystyle O(nlogn)\!}{\displaystyle O(nlogn)\!} پیدا می‌کند.
مرتب‌سازی شل	—	{\displaystyle {\mathcal {}}{n\log ^{2}n}}{\displaystyle {\mathcal {}}{n\log ^{2}n}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	خیر	درج	
مرتب‌سازی کتابخانه‌ای	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}n}{\displaystyle {\mathcal {}}n}	بله	درج	
مرتب‌سازی گورزاد	—	{\displaystyle {\mathcal {}}n^{2}}{\displaystyle {\mathcal {}}n^{2}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	بله	تعویض	کد کوتاه
مرتب‌سازی مسابقه‌ای	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}	{\displaystyle {\mathcal {O}}\left({n\log n}\right)}{\displaystyle {\mathcal {O}}\left({n\log n}\right)}			انتخاب	
مرتب‌سازی هرمی	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{n\log n}}{\displaystyle {\mathcal {}}{n\log n}}	{\displaystyle {\mathcal {}}{1}}{\displaystyle {\mathcal {}}{1}}	خیر	انتخاب
