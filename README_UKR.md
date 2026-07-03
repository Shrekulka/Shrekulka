# 📚 Shrekulka — Портфоліо розробника та проєкти

Ласкаво просимо до структурованого репозиторію проєктів розробника **Shrekulka**. Тут зібрані як комерційні продукти та самостійні розробки, так і розширене навчальне портфоліо, що охоплює системне програмування на **C/C++**, а також розробку вебдодатків, асинхронних ботів, інтеграцій та скриптів автоматизації на **Python**.

---

## 🌳 Структура репозиторіїв (Repository Structure)

    Shrekulka/
    │
    ├── educationalProjects/                             # 📚 Головне навчальне портфоліо (Python, C, C++)
    │   ├── c/                                           # Проєкти на мові C (системне та мережеве програмування)
    │   │   ├── Linux_kernel_modules/                    # Розработка модулів ядра Linux, що завантажуються (LKM)
    │   │   │   └── develop/kernel/                      # hello-1..5, chardev, ioctl, proc-1..4, sysfs, simple_hello
    │   │   ├── UNIX_Professionalnoe_programmirovanie_3-e_izd_2018/ # Вправи з книги Стівенса APUE
    │   │   │   └── directory_file_listing/              # Аналог ls через opendir()/readdir()
    │   │   ├── network_programming/                     # Мережеві додатки та утиліти на C
    │   │   │   ├── getaddrinfo_example/                 # Доменне (DNS) розв'язання імен хостів (IPv4/IPv6) через getaddrinfo
    │   │   │   ├── reverse_socks5_proxy/                # Реалізація зворотного (reverse) SOCKS5-проксі
    │   │   │   └── unix_network_development_applications/ # Шаблони проектування з книги Стівенса UNP
    │   │   │       ├── Time_and_Date_TCP_Client_and_Simple_Time_and_Date_Server/ # TCP-сервер часу + клієнт IPv4/IPv6
    │   │   │       └── pieces_of_code_for_network_programming/ # Порядок байтів, перетворення IP-адрес (4 підпапки)
    │   │   └── solutions_to_C_book_Exercises_Kernighan_Ritchie_3rd_Edition/ # 17 вправ K&R (1.6–1.22)
    │   │
    │   ├── c++/                                         # Проєкти на C++ (алгоритми, ООП, мережі)
    │   │   ├── TCPCommunication/                        # TCP-сервер та клієнт на BSD-сокетах
    │   │   │   ├── TCP Server/                          # Серверна частина
    │   │   │   └── TCPClient/                           # Клієнтська частина
    │   │   ├── algorithms/                              # Базові алгоритми
    │   │   │   ├── reverse_algorithm/                   # Реверс вектора через ітератори STL
    │   │   │   └── sorting/                             # 4 варіанти сортування
    │   │   │       ├── bubble_sort/bubble sort in reverse order/          # Бульбашкове у зворотному порядку
    │   │   │       ├── bubble_sort/bubble_sort_from_start_to_end_of_array/ # Бульбашкове у прямому порядку
    │   │   │       ├── bubble_sort/flag_bubble_sort/                      # Бульбашкове з прапором оптимізації
    │   │   │       ├── insertion_sort_algorithm_and_execution_time/       # Сортування вставками з вимірюванням часу роботи
    │   │   │       └── quick_sort/                                        # Швидке сортування
    │   │   ├── arrays/                                  # Робота з масивами та векторами
    │   │   │   ├── array_shuffling/                     # Перемішування з математичним контролем розподілу
    │   │   │   ├── max_number_in_array/                 # Пошук максимуму через апаратний генератор випадкових чисел (random_device)
    │   │   │   ├── output_array_in_ascending_order/     # Сортування бульбашкою за зростанням
    │   │   │   ├── unique_random_numbers_in_an_array/   # Унікальні числа через std::set
    │   │   │   └── working_with_dynamic_arrays/         # Виділення пам'яті new[], копіювання, delete[]
    │   │   │       └── dynamic_array_copy/              # Копіювання динамічного масиву з mt19937
    │   │   ├── class/                                   # Об'єктно-орієнтоване програмування на C++
    │   │   │   ├── class_singly_linked_list/            # Однозв'язний список без використання STL
    │   │   │   ├── class_string/                        # Кастомний клас рядків на char*
    │   │   │   ├── decorator_coffee_consol/             # Шаблон проєктування «Декоратор» для кавових замовлень
    │   │   │   ├── duck/                                # Шаблон проєктування «Стратегія» (Strategy pattern)
    │   │   │   ├── map_and_multimap/                    # Асоціативні контейнери std::map та std::multimap
    │   │   │   ├── matrix/                              # Матриця з перевантаженням [], +, *, <<
    │   │   │   ├── rectangle/                           # «Правило трьох»: деструктор, конструктор копіювання, operator=
    │   │   │   ├── stack_calculator/                    # Калькулятор на основі стека
    │   │   │   ├── stack_data_structure/                # Стек LIFO: push(), pop(), top(), isEmpty()
    │   │   │   └── tasks/                               # Додаткові завдання розділу class
    │   │   │       └── odd_numbers_to_beginning_even_numbers_to_end_array/ # Непарні на початок, парні в кінець вектора
    │   │   ├── dynamic_programming/                     # Динамічне програмування
    │   │   │   ├── counting_trajectories_from_city_to_city/ # Унікальні шляхи в орієнтованому ациклическому графі
    │   │   │   └── digital_herringbone/                 # Числовий шаблон «ялинка» у двовимірній структурі
    │   │   ├── lafore_task/                             # Завдання з підручника Роберта Лафоре
    │   │   │   ├── 3.1/ 3.2/ 3.3/ 3.4/                 # Основи класів та методів
    │   │   │   ├── chapter_4/                           # Перевантаження операторів та конструктори копіювання
    │   │   │   │   ├── 4.1/                             # Перевантаження операторів
    │   │   │   │   ├── 4.3/                             # Константные методы
    │   │   │   │   ├── card_game/                       # Карткова гра з перевантаженням операторів
    │   │   │   │   ├── english_system_of_measures/      # Система англійських мір
    │   │   │   │   ├── english_system_of_measures2/     # Розширена система англійських мір
    │   │   │   │   └── word_count/                      # Підрахунок слів
    │   │   │   └── chapter_7/                           # Віртуальні функції та поліморфізм
    │   │   │       ├── 7.1/                             # Віртуальні методи
    │   │   │       └── 7.2/                             # Абстрактні базові класи
    │   │   ├── struct/                                  # Користувацькі типи даних
    │   │   │   ├── queue/                               # Кільцева черга FIFO з динамічною пам'яттю
    │   │   │   └── students_name_and_grades/            # Картка студента з валідацією ПІБ та оцінок
    │   │   └── tasks/                                   # Навчальні завдання з C++
    │   │       ├── array_tasks/                         # Завдання на масиви
    │   │       │   ├── array_elements_increase_divide_by_first_element_decrease_by_number/
    │   │       │   ├── fill_0_1_2_3_4...and..._3_2_1_0/
    │   │       │   ├── finding_the_mode_of_a_number/
    │   │       │   └── search_element_index/
    │   │       └── various_tasks/                       # Різноманітні завдання
    │   │           ├── algorithm_of_lexicographic_sorting/ # Лексикографічне сортування рядків
    │   │           ├── find_the_number_of_times_the_light_is_turned_on/ # Підрахунок увімкнень світла
    │   │           ├── output_current_date/             # Виведення поточної дати
    │   │           ├── parentheses/stack_parentheses/   # Валідатор балансу дужок через стек
    │   │           ├── simple_tasks/                    # Прості завдання (мінімум/максимум, округлення, сортування, суми)
    │   │           └── triangle_check/                  # Перевірка можливості побудови трикутника
    │   │
    │   └── python/                                      # Основний розділ (Python)
    │       ├── ai/                                      # Проєкти з технологіями штучного інтелекту
    │       │   ├── generating_images_from_text_OpenAI_and_ChatGPT/ # OpenAI DALL-E API, збереження, JSON-лог
    │       │   └── web_crawler_ads_generator/           # cloudscraper → OpenAI summary → CSV для Google Ads
    │       ├── api/                                     # Інтеграція з REST-сервісами
    │       │   ├── email_email_checking_and_verification_hunter/ # Клієнт Hunter.io, валідація email
    │       │   ├── getting_access_token_to_artsynet_API_and_sorting/ # OAuth Artsy.net, сортування художників
    │       │   ├── hunter_check_mail/                   # Розширений Hunter.io: SQLite, меню, утиліти
    │       │   └── numbers_api_explorer/                # Запити до numbersapi.com (math/trivia/date)
    │       ├── audio_and_text/                          # Інструменти для роботи зі звуком та мовленням
    │       │   ├── add_words_and_music/                 # TTS + музика: вибір джерела тексту, об'єднання
    │       │   ├── convert_text_to_speech_in_python/    # TTS через lovoai API
    │       │   ├── speech_to_text_library_speech_recognition/ # Запис з мікрофона, вибір мови/якості
    │       │   └── transcription_of_text_from_an_audio_file/ # Whisper tiny/base/medium/large
    │       ├── BD/                                      # Робота з базами даних
    │       │   └── SQLite/                              # Приклади та завдання на СУБД SQLite
    │       │       ├── aggregation_and_grouping/        # COUNT, DISTINCT, GROUP BY, HAVING
    │       │       ├── commands_when_work_with_tables/  # CRUD + context manager для з'єднання
    │       │       └── first_steps_with_SQLite/         # Підключення, створення таблиць, запити
    │       ├── black_hat_python/                        # Мережеві утиліти за мотивами «Black Hat Python»
    │       │   ├── my_netcat/                           # NetCat: з'єднання, прослуховування, багатопотоковість
    │       │   ├── scan/                                # ARP/ICMP-сканер хостів у підмережі
    │       │   ├── tcp_client/                          # simple_tcp_client.py та розширений варіант
    │       │   ├── tcp_proxy/                           # Перехоплення трафіку з hexdump форматуванням
    │       │   ├── tcp_server/                          # Багатопотоковий сервер AF_INET + SOCK_STREAM
    │       │   └── udp_client/                          # AF_INET + SOCK_DGRAM, відправка та прийом
    │       ├── bots/                                    # Розробка Telegram-ботів
    │       │   ├── aiogram_2/                           # Боти на aiogram версії 2
    │       │   │   ├── ai_checklist_guardian/           # Вибір локації → чек-лист через OpenAI (aiogram v2.25)
    │       │   │   ├── telegram_bot/                    # Архітектурний приклад: хендлери, клавіатури, БД
    │       │   │   └── telegram_bot_inline/             # Inline-кнопки та обробка callback-запитів
    │       │   ├── aiogram_3/                           # Боти на aiogram версії 3
    │       │   │   ├── bot_guess_the_number/            # «Вгадай число» з SQLite
    │       │   │   ├── bot_guess_the_number_dictionary/ # «Вгадай число» з in-memory словником
    │       │   │   ├── bot_rock_paper_scissors/         # «Камінь-ножиці-папір» з Pydantic-конфігурацією
    │       │   │   ├── callback_data_factory/           # Типізовані callback через фабрику
    │       │   │   ├── edit_messages/                   # 3 способи редагування повідомлень
    │       │   │   ├── editing_messages_of_different_types/ # edit_message_media для заміни медіафайлів
    │       │   │   ├── form_filling_bot_fsm/            # FSM-анкета з діаграмою станів
    │       │   │   ├── formatting_text_in_messages/     # HTML, Markdown, кастомні сутності
    │       │   │   ├── improved_echo_bot/               # Ехо-бот з валідацією типів контенту
    │       │   │   ├── inline_buttons/                  # Inline-кнопки з URL та callback
    │       │   │   ├── inline_callback_buttons/         # Розширені callback-кнопки з медіафайлами
    │       │   │   ├── middleware_example_bot/          # Middleware: логування, throttling, права доступу
    │       │   │   ├── naval_combat_game/               # «Морський бій» на inline 8×8 сітці + FSM + SQLite
    │       │   │   ├── own_keyboard_generator/          # Функція create_inline_kb з довільною кількістю кнопок
    │       │   │   ├── regular_buttons_telegram_bot/    # Reply-кнопки
    │       │   │   ├── simple_echo_bot/                 # Базовий ехо-бот
    │       │   │   ├── telegram_bot_book/               # Читання книг з пагінацією та закладками в БД
    │       │   │   └── telegram_bot_menu_button/        # Команди через set_my_commands, кнопка Web App
    │       │   ├── kitties_bot/                         # Випадкові фото котів/собак через публічні API
    │       │   ├── telegram_bot_project_skeleton/       # Boilerplate: структура папок, .env, базовые команды
    │       │   └── youTube_video_search_bot/            # aiohttp + YouTube Data API v3
    │       ├── class/                                   # ООП на Python
    │       │   ├── Is_the_class_an_ancestor/            # Визначення предків/нащадків обходом графа
    │       │   ├── MoneyBox_for_working_with_a_virtual_piggy_bank/ # Скарбничка з контролем місткості
    │       │   ├── analogue_of_a_money_wallet/          # Гаманець: валюта (3 великі літери), баланс, операції
    │       │   ├── class_Transport/                     # Поліморфізм: Transport, Car, Boat, Plane
    │       │   ├── class_filter/                        # Мультифільтр — аналог вбудованого filter()
    │       │   ├── class_that_implements_an_iterator/   # RandomIterator через __next__()
    │       │   ├── create_class_Newlnt_inherited_from_int/ # Розширення int методом repeat(n)
    │       │   ├── implementation_of_PositiveList_class/ # Список з NonPositiveError при вставці ≤0
    │       │   ├── information_logging/                 # Міксин Loggable для автологування методів
    │       │   ├── people_with_a_sweet_tooth_vegetarians_meat_lovers/ # Класифікація харчових вподобань (Дніпро 2020)
    │       │   ├── stack_implementation/                # Розширений стек з арифметичними операціями (+,-,*,//)
    │       │   ├── sum_of_the_first_five_numbers/       # Клас Buffer: сума кожних 5 чисел поспіль
    │       │   └── tags_in_songs/                       # Теги-метадані для категоризації та пошуку об'єктів
    │       ├── crypto_world/                            # Криптовалюти
    │       │   ├── inter_exchange_arbitrage_bot/        # FastAPI + aiogram v3, CCXT (Binance/Bybit/OKX/KuCoin/YoBit), AI-аналіз новин
    │       │   └── yobit_bot/                           # Торговий бот YoBit: Docker, SQLAlchemy ORM, Alembic
    │       ├── CSV_JSON_text_file_formats/              # Аналіз структурованих форматів
    │       │   └── find_out_the_type_of_crime_that_was_recorded_the_maximum_number_of_times/ # Датасет злочинів Чикаго 2001–дотепер
    │       ├── django/                                  # Веб-додатки на Django
    │       │   ├── backend/                             # Блог/CMS: авторизация, CKEditor, Docker, Redis, Nginx
    │       │   ├── book_shop/                           # Книжковий інтернет-магазин з кошиком (в розробці)
    │       │   ├── buy_online_hub/                      # Структура Django-проєкту: goods, main, users
    │       │   ├── cinema_guide/                        # Кінопортал з жанровими фільтрами та оцінками
    │       │   ├── money_convert_django/                # Конвертер валют з моделлю ConversionHistory
    │       │   ├── portfolio_master/                    # Сайт-портфолио розробника
    │       │   ├── sitewomen/                           # Django-портал з ORM та медіафайлами
    │       │   └── zodiac_portal/                       # Гороскопи з динамічним роутингом URL
    │       ├── encrypt_and_decrypt/                     # Криптографія та безпека
    │       │   ├── creation_and_storage_of_logins_and_passwords/ # SQLite-менеджер паролів (клас BD)
    │       │   ├── encrypt_and_decrypt_PDF_file/        # Шифрування/дешифрування PDF з паролем
    │       │   ├── encrypt_and_decrypt_all_files_in_directories_pyAesCrypt/ # Рекурсивне AES-256, збереження .crp
    │       │   └── messages_to_images_and_back/         # Стеганографія + шифрування в пікселях PNG
    │       ├── fast_api/                                # Веб-сервіси на FastAPI
    │       │   ├── fast_api_post_manager/               # CRUD публікацій: Pydantic, SQLAlchemy, Alembic
    │       │   ├── lang_chain_fast_summarizer/          # FastAPI + LangChain → самаризація через LLM
    │       │   ├── quick_start_in_fastapi_python/       # 8 навчальних мікросервісів (auth, files, пошук, реєстрація…)
    │       │   └── restful_text_processing_with_nltk/   # Токенізація, стемінг, частотний аналіз через NLTK
    │       ├── flask/                                   # Веб-додатки на Flask
    │       │   ├── flask_database/                      # SQLAlchemy ORM з підтримкою міграцій
    │       │   ├── integration_telegram_planfix/        # Вебхук: синхронізація Telegram ↔ CRM Planfix
    │       │   ├── secure_hub/                          # Авторизація, сесії та захист роутів
    │       │   └── website_page_templates/              # Успадкування Jinja2-шаблонів, обробка 404/500
    │       ├── grpc/                                    # gRPC-сервіси на Python
    │       │   ├── bidirectional_streaming_chat_service/ # Двонаправлений потоковий чат
    │       │   ├── book_shop_grpc/                      # Каталог книг з пошуком на gRPC замість REST
    │       │   ├── client_streaming_average_calculator/ # Потік чисел від клієнта → середнє значення
    │       │   ├── grpc_example/                        # Hello World: компіляція .proto → Python-класи
    │       │   ├── streaming_grpc_string_analyzer/      # Server streaming: порційний аналіз рядка
    │       │   └── unary_grpc_calculator/               # Синхронний калькулятор (+, -, *, /) Unary RPC
    │       ├── ip/                                      # Мережеві дані
    │       │   └── getting_information_by_ip/           # ip-api.com: ISP/країна/координати + карта folium
    │       ├── photo/                                   # Обробка зображень
    │       │   ├── adding_text_to_photo/                # PIL: текст у заданих координатах, автовизначення шрифту
    │       │   └── text_from_image_using_tesseract/     # OCR: вибір мови/файлу, pytesseract
    │       ├── pyplot_graphics/                         # Наукова візуалізація (Matplotlib)
    │       │   ├── sin_function_plot_0_to_10/           # sin(x) на [0,10] з кроком 0.01 → sin.png
    │       │   └── trigonometric_plot.py                # sin + cos з різними стилями → trigan.png
    │       ├── scraper/                                 # Веб-скрапінг
    │       │   ├── Instagram_scraper_instaloader/       # Асинхронний збір даних профілів Instagram
    │       │   ├── business_web_scraper/                # Selenium: оголошення «бизнес» + вилучення телефонів
    │       │   ├── requests_and_beautiful_soup/         # sync_scraper + thread_scraper (lego)
    │       │   ├── scrapy/scraper_spider/               # Scrapy: books.toscrape.com з обходом пагінації
    │       │   ├── selenium/                            # Автоматизація входу на захищені сайти
    │       │   └── stepic/                              # 7 задач XML/HTML: OSM, Wikipedia, таблиці
    │       ├── spreadsheets/                            # Електронні таблиці
    │       │   ├── calculation_of_total_caloric_content_work_with_two_sheets/ # КБЖВ з двох аркушів, кома-розділювач
    │       │   ├── count_four_numbers_for_each_day/     # Меню кухаря: КБЖВ за днями через openpyxl
    │       │   ├── excel_phonebook_parser/              # aiogram 3.3.0 ехо-бот + парсинг Excel телефонної книги
    │       │   ├── finding_the_smallest_value/          # Мінімум у стовпці C з tab.xlsx
    │       │   ├── recover_payroll_from_payroll_records/ # «Роги та Копыта»: відновлення відомості з ZIP
    │       │   ├── sample_of_the_highest_average_salary/ # Регіон з найбільшою медіанною зарплатою
    │       │   ├── sort_by_product_name/                # Сортування продуктової таблиці за алфавітом
    │       │   └── work_with_Pandas/                    # DataFrame, фільтрація, групування
    │       ├── text/                                    # Аналіз тексту
    │       │   ├── fontman/                             # Заміна шрифту .docx на рукописний
    │       │   └── summarization_of_texts/              # TextRank: лематизація, схожість речень, ранжування
    │       ├── video_generation/                        # Мультимедіа
    │       │   └── short_video_generation/              # moviepy + YAML-конфіг → Reels/Shorts
    │       └── web/                                     # Системні веб-утилити
    │           ├── dns_proxy_blacklist/                 # DNS-проксі: blacklist + upstream з конфіг-файлу
    │           └── net_port_scanner/                    # asyncio-сканер, підтримка всіх інтерфейсів
    │
    ├── solana-webwallet/                                # ⭐ Telegram-бот для гаманців Solana (Python, Middle)
    └── tasks/                                           # 🗂️ Колекція прикладних та комерційних проєктів (Python)
        ├── auto_ria_tracker/                            # 🚗 AUTO.RIA Toyota Monitor Bot: нові оголошення, ціни, продажі
        ├── date_assistant/                              # 🤖 AI-асистент аналізу Instagram-профилів (FastAPI, LLM)
        ├── email_blast/                                 # 📧 Персоналізована розсилка, батчі по 10 000 листів з CSV
        ├── email_sorter_pro/                            # 🔍 Сортування 200 ГБ баз email за країнами, невідомі → OTHER
        ├── fat32_disk_emulation/                        # 💾 FAT32-диск 20 МБ, команди dir/cd/mkdir/create/cat/rename
        ├── guess_the_card_game/                         # 🃏 6 спроб: вгадай колір/масть/номінал карти
        ├── human_body_mass_index/                       # ⚖️ ІМТ за ВООЗ: 5 категорій (Underweight → Obese)
        ├── numeric_data_file_analyzer/                  # 📊 Max, min, медіана, середнє + найдовші послідовності
        ├── order-management-service/                    # 📦 K2 ERP: Клієнт/Товар/Замовлення, DRF, TypeScript, Docker
        ├── scraper/artikul_price_tracker/               # 🛒 Трекер цін Wildberries за артикулами (Selenium + openpyxl)
        └── task_manager/                                # 📋 Django + HTMX: проєкти, задачі, дедлайни, Docker

---

## 📄 Детальний опис проєктів та розділів

### 1. Самостійні репозиторії (основний профіль)

#### `solana-webwallet`
- **Опис:** Telegram-бот на базі `aiogram` — некастодіальний гаманець Solana безпосередньо у чаті.
- **Функції:** генерація та імпорт гаманців за допомогою мнемонічної фрази, збереження ключів, перевірка балансу SOL, відправка та отримання токенів, перегляд історії транзакцій.
- **Реалізація:** розподіл логіки на шари `handlers` (обробники), `keyboards` (клавіатури), `external_services` (запити до JSON-RPC нод Solana), `database` (робота з базою даних). Налаштовано запуск у Docker-контейнері.

#### `tasks`
- **Опис:** Колекція практичних інструментів автоматизації, комерційних розробок та прикладних завдань.
- **Реалізація:**
  - `auto_ria_tracker` — Телеграм-бот «AUTO.RIA Toyota Monitor Bot»: відстежує появу нових оголошень, зниження цін та продаж автівок марки Toyota. Періодично збирає дані з HTML-сторінок, порівнює записи з локальною базою даних SQLite та надсилає повідомлення користувачам через aiogram v3.
  - `date_assistant` — Асистент зі штучним інтелектом: виконує аналіз відкритих Instagram-профілів та надає індивідуальні рекомендації за допомогою інтеграції великих мовних моделей (OpenAI, Claude, DeepSeek). Підтримує потокове передавання відповідей (streaming) та має модульну архітектуру провайдерів ШІ.
  - `email_blast` — Інструмент для персоналізованої email-розсилки, що підтримує надсилання листів пакетами до десяти тисяч адрес із CSV-файлів та веде детальний журнал результатів відправки.
  - `email_sorter_pro` — Скрипт для сортування великих баз email-адрес загальним обсягом до двохсот гігабайтів за країнами. Працює на основі гнучких конфігурацій доменних зон; невідомі домени перенаправляє до папки OTHER.
  - `fat32_disk_emulation` — Програмний емулятор віртуального диска ємністю двадцять мегабайтів із файловою системою FAT32. Підтримує термінальні команди навігації та керування файлами: `dir`, `cd`, `mkdir`, `create`, `cat`, `rename`.
  - `guess_the_card_game` — Консольна гра з вгадування параметрів карт із віртуальної колоди на п'ятдесят дві карти з обмеженням до шести спроб на кожну категорію питань.
  - `human_body_mass_index` — Калькулятор індексу маси тіла, що розподіляє результати за п'ятьма офіційними категоріями Всесвітньої організації охорони здоров'я.
  - `numeric_data_file_analyzer` — Скрипт для статистичного аналізу великих текстових файлів із цілими числами. Обчислює мінімальне, максимальне, медіанне та середнє значення, а також визначає найдовші безперервні послідовності чисел за зростанням та спаданням.
  - `order-management-service` — Модуль обліку замовлень для K2 Enterprise Resource Planning. Оперує сутностями Клієнт, Товар та Замовлення. Має програмний інтерфейс REST API на базі Django Rest Framework, форми взаємодії на TypeScript, запуск через Docker, документацію Swagger/ReDoc та тестове покриття за допомогою pytest.
  - `scraper/artikul_price_tracker` — Монітор цін на товари Wildberries за вказаними артикулами. Використовує Selenium для обходу систем захисту сайту та формує Excel-звіти за допомогою openpyxl.
  - `task_manager` — Вебдодаток для керування проєктами та задачами, створений на Django та HTMX, що дозволяє оновлювати статус завдань без перезавантаження вебсторінки. Налаштовані конфігурації розгортання для розробки та продуктового середовища із використанням Nginx та PostgreSQL.

---

### 2. Системне програмування на мові C (`educationalProjects / C`)

#### `Linux_kernel_modules`
- `hello-1..5` — Навчальні модулі ядра на Ubuntu, що демонструють життєвий цикл LKM, параметри ініціалізації та обробку метаданих.
- `chardev/character_driver_for_tracking_reads` — Драйвер символьного пристрою з внутрішнім лічильником системних викликів читання.
- `chardev/ioctl` — Драйвер пристрою з підтримкою індивідуальних керуючих викликів ioctl.
- `proc/proc-1..4` — Чотири різні методи реалізації інтерфейсу взаємодії з файловою системою `/proc` (включаючи seq_file).
- `sysfs/hello-sysfs` — Експорт параметрів модулів ядра у простір користувача через атрибути sysfs.
- `simple_hello` — Навчальний аналіз компіляції низькорівневих програм за допомогою gcc та відстеження системних викликів через strace.

#### `UNIX_Professionalnoe_programmirovanie_3-e_izd_2018`
- `directory_file_listing` — Альтернативна реалізація стандартної утиліти `ls` з форматованим виведенням метаданих файлів за допомогою системних функцій `opendir()` та `readdir()`.

#### `network_programming`
- `getaddrinfo_example` — Розв'язання доменних імен хостів в IPv4 та IPv6 адреси за допомогою структури `addrinfo`.
- `reverse_socks5_proxy` — Зворотний проксі-сервер SOCKS5, який дозволяє клієнту всередині захищеної мережі ініціювати вихідне з'єднання для подальшого віддаленого доступу.
- `unix_network_development_applications`:
  - `Time_and_Date_TCP_Client_and_Simple_Time_and_Date_Server` — Простий TCP-сервер точного часу та відповідні клієнти для протоколів IPv4/IPv6.
  - `pieces_of_code_for_network_programming` — Приклади коду для перетворення мережевих адрес та визначення порядку байтів у пам'яті.
  - `UNIX_Network_Development_3rd_Edition/unpv13e` — Мережеві шаблони програмування сокетів, мультиплексування введення-виведення (`select`, `poll`, `epoll`) та мережевої діагностики з книги Стівенса UNIX Network Programming.

#### `solutions_to_C_book_Exercises_Kernighan_Ritchie_3rd_Edition`
Сімнадцять вправ із першого розділу класичного підручника Кернігана та Річі з мови C: обробка потоків введення, видалення зайвих пробілів, побудова гістограм символів та алгоритми реверсу рядків.

---

### 3. Алгоритми та об'єктно-орієнтоване програмування на C++ (`educationalProjects / C++`)

#### `TCPCommunication`
Клієнт-серверна взаємодія на базі низькорівневих BSD-сокетів. Сервер очікує підключення, а клієнт надсилає текстові пакети даних.

#### `algorithms/sorting`
Чотири алгоритми сортування масивів: бульбашкове сортування у звичайному, зворотному та оптимізованому (із прапором змін) варіантах, сортування вставками з профілюванням часу та швидке сортування (quicksort).

#### `arrays/working_with_dynamic_arrays`
Робота з динамічною пам'яттю на купі (heap): виділення масивів через new[], копіювання, заповнення елементів за допомогою генератора mt19937 та очищення через delete[].

#### `class`
- `class_singly_linked_list` — Однозв'язний список, реалізований без залучення бібліотеки STL.
- `class_string` — Клас керування рядками на базі покажчиків `char*` з ручним виділенням пам'яті та конструкторами глибокого копіювання.
- `decorator_coffee_consol` — Програмна демонстрація шаблону проєктування «Декоратор» на прикладі розрахунку вартості кавових напоїв.
- `duck` — Шаблон проєктування «Стратегія» для динамічної зміни поведінки об'єктів під час виконання програми.
- `map_and_multimap` — Робота з асоціативними контейнерами `std::map` та `std::multimap`.
- `matrix` — Клас математичної матриці з перевантаженими операторами доступу по індексу `[]`, додавання `+`, множення `*` та потокового виведення `<<`.
- `rectangle` — Демонстрація концепції «Правила трьох» (конструктор копіювання, оператор присвоєння, деструктор).
- `stack_calculator` — Математичний обчислювач виразів на основі стекової структури даних.
- `stack_data_structure` — Реалізація структури даних стек (LIFO) з базовими методами `push`, `pop`, `top` та `isEmpty`.
- `tasks/odd_numbers_to_beginning_even_numbers_to_end_array` — Алгоритм переміщення непарних елементів на початок, а парних — в кінець динамічного вектора.

#### `dynamic_programming`
- `counting_trajectories_from_city_to_city` — Підрахунок кількості унікальних маршрутів між вершинами в орієнтованих ациклічних графах.
- `digital_herringbone` — Пошук оптимального шляху з максимальною сумою у трикутній матричній структурі.

#### `lafore_task`
Завдання з підручника Роберта Лафоре:
- `3.1–3.4` — Створення базових класів, методів та структур даних.
- `chapter_4` — Перевантаження арифметичних операторів, константні методи, симуляція карткових ігор та перетворення англійських мір.
- `chapter_7` — Робота з віртуальними функціями, поліморфними викликами та чистими абстрактними класами.

#### `struct`
- `queue` — Реалізація кільцевої черги (FIFO) з динамічним виділенням пам'яті.
- `students_name_and_grades` — Клас студентської картки з валідацією текстових ПІБ та числових оцінок.

#### `tasks/various_tasks`
- `algorithm_of_lexicographic_sorting` — Алгоритм лексикографічного сортування текстових рядків.
- `parentheses/stack_parentheses` — Перевірка збалансованості дужок у тексті за допомогою стека.
- `simple_tasks` — Завдання на знаходження екстремумів, округлення чисел та обчислення сум числових послідовностей.

---

### 4. Інструменти та вебдодатки на Python (`educationalProjects / Python`)

#### `ai`
- `generating_images_from_text_OpenAI_and_ChatGPT` — Генерація зображень за текстовим описом за допомогою інтерфейсу DALL-E, збереження результатів на диск та логування запитів у JSON.
- `web_crawler_ads_generator` — Збір інформації з вебсторінок через cloudscraper, створення короткого опису за допомогою моделей OpenAI та експорт готових оголошень у CSV-формат для Google Ads.

#### `api`
- `email_email_checking_and_verification_hunter` — Клієнт для взаємодії з сервісом перевірки електронних адрес Hunter.io.
- `getting_access_token_to_artsynet_API_and_sorting` — Авторизація OAuth 2.0 та збір інформації про художників на Artsy.net із сортуванням результатів.
- `hunter_check_mail` — Програма для пакетної валідації поштових скриньок за доменом із збереженням результатів у локальну базу даних SQLite.
- `numbers_api_explorer` — Консольне меню для отримання історичних та математичних фактів про числа з numbersapi.com.

#### `audio_and_text`
- `add_words_and_music` — Перетворення введеного тексту або текстових файлів у мовлення з подальшим накладанням музичного супроводу.
- `convert_text_to_speech_in_python` — Синтез мовлення за допомогою сервісу lovoai API.
- `speech_to_text_library_speech_recognition` — Запис звуку з мікрофона з можливістю вибору параметрів якості та розпізнаванням тексту.
- `transcription_of_text_from_an_audio_file` — Порівняльний аналіз швидкості та якості транскрипції аудіофайлів різними моделями Whisper.

#### `BD/SQLite`
- `aggregation_and_grouping` — SQL-запити групування та агрегації даних (COUNT, GROUP BY, HAVING).
- `commands_when_work_with_tables` — CRUD-операції в таблицях SQLite з використанням менеджерів контексту для керування транзакціями.
- `first_steps_with_SQLite` — Створення таблиць, налаштування індексів та базові пошукові запити.

#### `black_hat_python`
- `my_netcat` — Реалізація утиліти NetCat на сокетах Python із підтримкою віддаленого командного рядка та багатопотокового очікування з'єднань.
- `scan` — Мережевий сканер хостів в локальному сегменті за допомогою ARP та ICMP запитів.
- `tcp_client` / `udp_client` — Шаблони для відправки та отримання мережевих пакетів через протоколи TCP та UDP.
- `tcp_proxy` — Мережевий проксі-сервер для перехоплення та модифікації транзитного трафіку з виведенням у форматі hexdump.

#### `bots / aiogram_2` та `aiogram_3`
- `ai_checklist_guardian` — Бот на aiogram v2, що генерує індивідуальні інструкції для поїздок через OpenAI.
- `bot_guess_the_number` — Гра «Вгадай число» зі збереженням прогресу користувачів у SQLite.
- `bot_rock_paper_scissors` — Гра «Камінь-ножиці-папір» з валідацією налаштувань через Pydantic.
- `callback_data_factory` — Обробка натискань клавіатур за допомогою типізованих фабрик даних Callback Data.
- `edit_messages` / `editing_messages_of_different_types` — Способи динамічного оновлення тексту та заміни медіафайлів у повідомленнях бота.
- `form_filling_bot_fsm` — Опитування користувачів з побудовою ланцюжків станів за допомогою скінченних автоматів (FSM).
- `formatting_text_in_messages` — Оформлення надісланих повідомлень за допомогою HTML, Markdown та кастомних сутностей Telegram.
- `improved_echo_bot` — Ехо-бот з валідацією типів отриманого контенту.
- `middleware_example_bot` — Приклад проміжного програмного забезпечення (middleware) для обмеження частоти запитів (throttling), логування та перевірки прав.
- `naval_combat_game` — Гра «Морський бій» на сітці 8x8, побудованій на базі inline-кнопок, з підтримкою сесій в SQLite.
- `telegram_bot_book` — Бот для читання електронних книг із збереженням закладок користувачів у базі даних.

#### `class`
- `Is_the_class_an_ancestor` — Алгоритм обходу графа спадкування для виявлення зв'язків між класами.
- `MoneyBox_for_working_with_a_virtual_piggy_bank` — Клас віртуальної скарбнички, що обмежує перевищення ліміту завантажених монет.
- `analogue_of_a_money_wallet` — Клас мультивалютного гаманця з перевіркою кодів ISO та методами конвертації.
- `class_filter` — Реалізація класу-мультифільтра, що працює за протоколом ітератора та імітує логіку вбудованої функції filter().
- `information_logging` — Клас-mixin для автоматичного логування викликів методів у спадкоємцях.

#### `crypto_world`
- `inter_exchange_arbitrage_bot` — Вебсервіс на FastAPI та aiogram v3, що використовує бібліотеку CCXT для відстеження арбітражних вікон на криптовалютних біржах та аналізує новинний фон через інтеграцію з мовними моделями.
- `yobit_bot` — Торговий бот для біржі YoBit з використанням SQLAlchemy ORM, міграцій Alembic та можливістю розгортання в Docker.

#### `django`
- `backend` — Інформаційний блог з авторизацією користувачів, коментарями, інтегрованим CKEditor, Redis-кешуванням та зворотним проксі Nginx.
- `money_convert_django` — Вебконвертер валют із записом історії операцій у базу даних.
- `sitewomen` — Багатосторінковий портал з оптимізованими SQL-запитами Django ORM та використанням кастомних тегів шаблонів.
- `zodiac_portal` — Інформаційний сайт про знаки зодіаку з динамічною маршрутизацією URL-адрес.

#### `encrypt_and_decrypt`
- `creation_and_storage_of_logins_and_passwords` — Менеджер збереження паролів, що реалізує інтерфейс доступу до зашифрованої бази даних SQLite.
- `encrypt_and_decrypt_PDF_file` — Утиліта командного рядка для парольного шифрування та дешифрування PDF-документів.
- `encrypt_and_decrypt_all_files_in_directories_pyAesCrypt` — Рекурсивне шифрування файлів у директоріях за алгоритмом AES-256 із збереженням оригінальної структури папок.

#### `fast_api`
- `lang_chain_fast_summarizer` — Вебсервіс на FastAPI для автоматичного стиснення великих обсягів тексту за допомогою LangChain та моделей штучного інтелекту.
- `quick_start_in_fastapi_python` — Набір з восьми мікросервісів, що демонструють авторизацію за допомогою cookie, завантаження файлів та обробку запитів користувачів.

#### `spreadsheets`
- `excel_phonebook_parser` — Бот на aiogram v3, що розбирає завантажені Excel-файли та здійснює пошук контактів.
- `recover_payroll_from_payroll_records` — Скрипт для розпакування ZIP-архівів та відновлення відомостей нарахування заробітної плати.
- `work_with_Pandas` — Аналітичні операції над табличними даними за допомогою бібліотеки Pandas.

#### `text`
- `fontman` — Утиліта для модифікації документів Microsoft Word (.docx) шляхом заміни оригінальних шрифтів на імітацію рукописного тексту із збереженням форматування.
- `summarization_of_texts` — Реалізація алгоритму TextRank для виявлення найбільш значущих речень у текстових масивах на основі лематизації та матриць схожості.

---

## ⚠️ Директорії без документації (потребують створення README)

Нижче наведено список папок у репозиторії, які наразі не мають власних файлів документації README. Створення описів для них є запланованим завданням:

    C++:
      c++/class/duck/
      c++/lafore_task/3.1/ 3.2/ 3.3/ 3.4/
      c++/lafore_task/chapter_4/4.1/ 4.3/ card_game/ english_system_of_measures/ english_system_of_measures2/ word_count/
      c++/lafore_task/chapter_7/7.1/ 7.2/
      c++/tasks/various_tasks/find_the_number_of_times_the_light_is_turned_on/
    
    C:
      c/network_programming/getaddrinfo_example/
      c/network_programming/reverse_socks5_proxy/
    
    Python:
      python/bots/aiogram_2/telegram_bot_inline/
      python/django/book_shop/                     (Перебуває в процесі розробки)
      python/django/cinema_guide/
      python/django/portfolio_master/
      python/django/sitewomen/
      python/fast_api/fast_api_post_manager/       (Порожня папка проєкту)
      python/fast_api/lang_chain_fast_summarizer/
      python/flask/secure_hub/
      python/grpc/book_shop_grpc/                  (Порожня папка проєкту)
      python/grpc/grpc_example/
      python/scraper/scrapy/
      python/black_hat_python/scan/
      python/video_generation/short_video_generation/
      python/text/fontman/
    
    tasks:
      tasks/date_assistant/                        (Порожня папка проєкту)
      tasks/scraper/artikul_price_tracker/