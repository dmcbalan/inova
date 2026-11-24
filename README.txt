INOVA — сайт-візитка магазину смартфонів і аксесуарів (Мукачево)
================================================================
index.html            головна сторінка, українська (весь текст — звичайний HTML, можна редагувати)
en/index.html         англійська версія (окремий файл: зміни в index.html треба повторити і тут)
404.html              сторінка «не знайдено»
favicon.svg, site.webmanifest, robots.txt, sitemap.xml
assets/images/        logo-inova.png (логотип без фону, шапка й підвал)
                      store-entrance.jpg, store-hall.jpg (фото магазину)
                      duck-boss.png (hero), duck-cigar.png (банер), duck-cash.png (404)
                      PNG з прозорим фоном в оригінальній якості, ~8,5 МБ разом. Перед публікацією стиснути БЕЗ зменшення розміру
                      через tinypng.com (зберігає прозорість, вага падає в 3-4 рази, якість на око та сама)

НАЛАШТУВАННЯ — у кінці index.html та en/index.html (в обох!), блок «НАЛАШТУВАННЯ»:
  phone     — номер для Viber / WhatsApp / Telegram (зараз 380961189999)
  telegram  — username Telegram без @, якщо є (тоді чат відкриється з готовим текстом)
  email     — пошта для заявок з форми. Працює через formsubmit.co:
              після першої заявки на цю пошту прийде лист «Activate» — натисніть його один раз.
              Поки стоїть YOUR-EMAIL@gmail.com, форма відкриває поштову програму.
  tgHook    — адреса Google Apps Script, що пересилає заявки в Telegram
              (скрипт: ../inova-telegram-form.gs). Можна і tgHook, і email — тоді заявка йде в обидва місця.
Соцмережі (шапка, мобільне меню, підвал): посилання в блоках <div class="soc"> — Facebook зараз facebook.com/inova, замініть на справжній.

АДРЕСА САЙТУ: https://balanstudy.com.ua/inova/ (тимчасова). При переїзді на свій домен замініть її у index.html, en/index.html, robots.txt, sitemap.xml, а в 404.html — шляхи /inova/.
Фото бажано замінити на якісніші (від 1200px по ширині) з тими ж назвами файлів.
