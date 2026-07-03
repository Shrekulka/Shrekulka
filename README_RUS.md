# 📚 Shrekulka — Developer Portfolio & Projects

Добро пожаловать в структурированный репозиторий проектов разработчика **Shrekulka**. Здесь собраны как коммерческие и самостоятельные продукты, так и обширное образовательное портфолио, охватывающее системное программирование на **C/C++**, а также разработку веб-приложений, асинхронных ботов, интеграций и скриптов автоматизации на **Python**.

---

## 🌳 Структура репозиториев (Repository Structure)

```text
Shrekulka/
│
├── educationalProjects/                             # 📚 Главное учебное портфолио (Python, C, C++)
│   ├── c/                                           # Проекты на языке C (системное и сетевое программирование)
│   │   ├── Linux_kernel_modules/                    # Разработка загружаемых модулей ядра Linux (LKM)
│   │   │   └── develop/kernel/                      # hello-1..5, chardev, ioctl, proc-1..4, sysfs, simple_hello
│   │   ├── UNIX_Professionalnoe_programmirovanie_3-e_izd_2018/ # Упражнения из книги Стивенса APUE
│   │   │   └── directory_file_listing/              # Аналог ls через opendir()/readdir()
│   │   ├── network_programming/                     # Сетевые приложения и утилиты на C
│   │   │   ├── getaddrinfo_example/                 # DNS‑разрешение имён хостов (IPv4/IPv6) через getaddrinfo
│   │   │   ├── reverse_socks5_proxy/                # Реализация обратного (reverse) SOCKS5‑прокси
│   │   │   └── unix_network_development_applications/ # Паттерны из книги Стивенса UNP
│   │   │       ├── Time_and_Date_TCP_Client_and_Simple_Time_and_Date_Server/ # TCP сервер времени + клиент IPv4/IPv6
│   │   │       └── pieces_of_code_for_network_programming/ # Порядок байтов, преобразования IP‑адресов (4 подпапки)
│   │   └── solutions_to_C_book_Exercises_Kernighan_Ritchie_3rd_Edition/ # 17 упражнений K&R (1.6–1.22)
│   │
│   ├── c++/                                         # Проекты на C++ (алгоритмы, ООП, сети)
│   │   ├── TCPCommunication/                        # TCP‑сервер и клиент на BSD‑сокетах
│   │   │   ├── TCP Server/                          # Серверная часть
│   │   │   └── TCPClient/                           # Клиентская часть
│   │   ├── algorithms/                              # Базовые алгоритмы
│   │   │   ├── reverse_algorithm/                   # Реверс вектора через итераторы STL
│   │   │   └── sorting/                             # 4 варианта сортировки
│   │   │       ├── bubble_sort/bubble sort in reverse order/          # Пузырьковая в обратном порядке
│   │   │       ├── bubble_sort/bubble_sort_from_start_to_end_of_array/ # Пузырьковая в прямом порядке
│   │   │       ├── bubble_sort/flag_bubble_sort/                      # Пузырьковая с флагом оптимизации
│   │   │       ├── insertion_sort_algorithm_and_execution_time/       # Сортировка вставками с замером времени
│   │   │       └── quick_sort/                                        # Быстрая сортировка
│   │   ├── arrays/                                  # Работа с массивами и векторами
│   │   │   ├── array_shuffling/                     # Перемешивание с математическим контролем распределения
│   │   │   ├── max_number_in_array/                 # Поиск максимума через аппаратный RNG (random_device)
│   │   │   ├── output_array_in_ascending_order/     # Сортировка пузырьком по возрастанию
│   │   │   ├── unique_random_numbers_in_an_array/   # Уникальные числа через std::set
│   │   │   └── working_with_dynamic_arrays/         # Выделение памяти new[], копирование, delete[]
│   │   │       └── dynamic_array_copy/              # Копирование динамического массива с mt19937
│   │   ├── class/                                   # Объектно‑ориентированное программирование на C++
│   │   │   ├── class_singly_linked_list/            # Односвязный список без STL
│   │   │   ├── class_string/                        # Кастомный класс строк на char*
│   │   │   ├── decorator_coffee_consol/             # Паттерн «Декоратор» для кофейных заказов
│   │   │   ├── duck/                                # Паттерн «Стратегия» (Strategy pattern)
│   │   │   ├── map_and_multimap/                    # Ассоциативные контейнеры std::map и std::multimap
│   │   │   ├── matrix/                              # Матрица с перегрузкой [], +, *, <<
│   │   │   ├── rectangle/                           # «Правило трёх»: деструктор, конструктор копирования, operator=
│   │   │   ├── stack_calculator/                    # Калькулятор на основе стека
│   │   │   ├── stack_data_structure/                # Стек LIFO: push(), pop(), top(), isEmpty()
│   │   │   └── tasks/                               # Дополнительные задачи раздела class
│   │   │       └── odd_numbers_to_beginning_even_numbers_to_end_array/ # Нечётные в начало, чётные в конец вектора
│   │   ├── dynamic_programming/                     # Динамическое программирование
│   │   │   ├── counting_trajectories_from_city_to_city/ # Уникальные пути в ориентированном ациклическом графе
│   │   │   └── digital_herringbone/                 # Числовой паттерн «ёлочка» в двумерной структуре
│   │   ├── lafore_task/                             # Задания из учебника Роберта Лафоре
│   │   │   ├── 3.1/ 3.2/ 3.3/ 3.4/                 # Основы классов и методов
│   │   │   ├── chapter_4/                           # Перегрузка операторов и конструкторы копирования
│   │   │   │   ├── 4.1/                             # Перегрузка операторов
│   │   │   │   ├── 4.3/                             # Константные методы
│   │   │   │   ├── card_game/                       # Карточная игра с перегрузкой операторов
│   │   │   │   ├── english_system_of_measures/      # Система английских мер
│   │   │   │   ├── english_system_of_measures2/     # Расширенная система английских мер
│   │   │   │   └── word_count/                      # Подсчёт слов
│   │   │   └── chapter_7/                           # Виртуальные функции и полиморфизм
│   │   │       ├── 7.1/                             # Виртуальные методы
│   │   │       └── 7.2/                             # Абстрактные базовые классы
│   │   ├── struct/                                  # Пользовательские типы данных
│   │   │   ├── queue/                               # Кольцевая очередь FIFO с динамической памятью
│   │   │   └── students_name_and_grades/            # Карточка студента с валидацией ФИО и оценок
│   │   └── tasks/                                   # Учебные задачи по C++
│   │       ├── array_tasks/                         # Задачи на массивы
│   │       │   ├── array_elements_increase_divide_by_first_element_decrease_by_number/
│   │       │   ├── fill_0_1_2_3_4...and..._3_2_1_0/
│   │       │   ├── finding_the_mode_of_a_number/
│   │       │   └── search_element_index/
│   │       └── various_tasks/                       # Разнообразные задачи
│   │           ├── algorithm_of_lexicographic_sorting/ # Лексикографическая сортировка строк
│   │           ├── find_the_number_of_times_the_light_is_turned_on/ # Подсчёт включений света
│   │           ├── output_current_date/             # Вывод текущей даты
│   │           ├── parentheses/stack_parentheses/   # Валидатор баланса скобок через стек
│   │           ├── simple_tasks/                    # Простые задачи (min/max, округление, сортировка, суммы)
│   │           └── triangle_check/                  # Проверка возможности построения треугольника
│   │
│   └── python/                                      # Основной раздел (Python)
│       ├── ai/                                      # Проекты с ИИ‑технологиями
│       │   ├── generating_images_from_text_OpenAI_and_ChatGPT/ # DALL-E API, сохранение, JSON-лог
│       │   └── web_crawler_ads_generator/           # cloudscraper → OpenAI summary → CSV для Google Ads
│       ├── api/                                     # Интеграция с REST‑сервисами
│       │   ├── email_email_checking_and_verification_hunter/ # Клиент Hunter.io, валидация email
│       │   ├── getting_access_token_to_artsynet_API_and_sorting/ # OAuth Artsy.net, сортировка художников
│       │   ├── hunter_check_mail/                   # Расширенный Hunter.io: SQLite, меню, утилиты
│       │   └── numbers_api_explorer/                # Запросы к numbersapi.com (math/trivia/date)
│       ├── audio_and_text/                          # Инструменты для работы со звуком и речью
│       │   ├── add_words_and_music/                 # TTS + музыка: выбор источника текста, объединение
│       │   ├── convert_text_to_speech_in_python/    # TTS через lovoai API
│       │   ├── speech_to_text_library_speech_recognition/ # Запись с микрофона, выбор языка/качества
│       │   └── transcription_of_text_from_an_audio_file/ # Whisper tiny/base/medium/large
│       ├── BD/                                      # Работа с базами данных
│       │   └── SQLite/                              # Примеры и задачи на СУБД SQLite
│       │       ├── aggregation_and_grouping/        # COUNT, DISTINCT, GROUP BY, HAVING
│       │       ├── commands_when_work_with_tables/  # CRUD + context manager для соединения
│       │       └── first_steps_with_SQLite/         # Подключение, создание таблиц, запросы
│       ├── black_hat_python/                        # Сетевые утилиты по мотивам «Black Hat Python»
│       │   ├── my_netcat/                           # NetCat: соединение, прослушивание, многопоточность
│       │   ├── scan/                                # ARP/ICMP-сканер хостов в подсети
│       │   ├── tcp_client/                          # simple_tcp_client.py и расширенный вариант
│       │   ├── tcp_proxy/                           # Перехват трафика с hexdump форматированием
│       │   ├── tcp_server/                          # Многопоточный сервер AF_INET + SOCK_STREAM
│       │   └── udp_client/                          # AF_INET + SOCK_DGRAM, отправка и приём
│       ├── bots/                                    # Разработка Telegram‑ботов
│       │   ├── aiogram_2/                           # Боты на aiogram v2
│       │   │   ├── ai_checklist_guardian/           # Выбор локации → чеклист через OpenAI (aiogram v2.25)
│       │   │   ├── telegram_bot/                    # Архитектурный пример: хендлеры, клавиатуры, БД
│       │   │   └── telegram_bot_inline/             # Inline‑кнопки и обработка callback‑запросов
│       │   ├── aiogram_3/                           # Боты на aiogram v3
│       │   │   ├── bot_guess_the_number/            # «Угадай число» с SQLite
│       │   │   ├── bot_guess_the_number_dictionary/ # «Угадай число» с in‑memory словарём
│       │   │   ├── bot_rock_paper_scissors/         # «Камень-ножницы-бумага» с Pydantic-конфигурацией
│       │   │   ├── callback_data_factory/           # Типизированные callback через фабрику
│       │   │   ├── edit_messages/                   # 3 способа редактирования сообщений
│       │   │   ├── editing_messages_of_different_types/ # edit_message_media для замены медиафайлов
│       │   │   ├── form_filling_bot_fsm/            # FSM-анкета с диаграммой состояний
│       │   │   ├── formatting_text_in_messages/     # HTML, Markdown, кастомные сущности
│       │   │   ├── improved_echo_bot/               # Эхо-бот с валидацией типов контента
│       │   │   ├── inline_buttons/                  # Inline‑кнопки с URL и callback
│       │   │   ├── inline_callback_buttons/         # Расширенные callback‑кнопки с медиафайлами
│       │   │   ├── middleware_example_bot/          # Middleware: логирование, throttling, права доступа
│       │   │   ├── naval_combat_game/               # «Морской бой» на inline 8×8 сетке + FSM + SQLite
│       │   │   ├── own_keyboard_generator/          # Функция create_inline_kb с произвольным числом кнопок
│       │   │   ├── regular_buttons_telegram_bot/    # Reply‑кнопки
│       │   │   ├── simple_echo_bot/                 # Базовый эхо‑бот
│       │   │   ├── telegram_bot_book/               # Чтение книг с пагинацией и закладками в БД
│       │   │   └── telegram_bot_menu_button/        # Команды через set_my_commands, кнопка Web App
│       │   ├── kitties_bot/                         # Случайные фото кошек/собак через публичные API
│       │   ├── telegram_bot_project_skeleton/       # Boilerplate: структура папок, .env, базовые команды
│       │   └── youTube_video_search_bot/            # aiohttp + YouTube Data API v3
│       ├── class/                                   # ООП на Python
│       │   ├── Is_the_class_an_ancestor/            # Определение предков/потомков обходом графа
│       │   ├── MoneyBox_for_working_with_a_virtual_piggy_bank/ # Копилка с контролем вместимости
│       │   ├── analogue_of_a_money_wallet/          # Кошелёк: валюта (3 заглавных буквы), баланс, операции
│       │   ├── class_Transport/                     # Полиморфизм: Transport, Car, Boat, Plane
│       │   ├── class_filter/                        # Мультифильтр — аналог встроенного filter()
│       │   ├── class_that_implements_an_iterator/   # RandomIterator через __next__()
│       │   ├── create_class_Newlnt_inherited_from_int/ # Расширение int методом repeat(n)
│       │   ├── implementation_of_PositiveList_class/ # Список с NonPositiveError при вставке ≤0
│       │   ├── information_logging/                 # Миксин Loggable для автологирования методов
│       │   ├── people_with_a_sweet_tooth_vegetarians_meat_lovers/ # Классификация пищевых предпочтений (Днепр 2020)
│       │   ├── stack_implementation/                # Расширенный стек с арифметическими операциями (+,-,*,//)
│       │   ├── sum_of_the_first_five_numbers/       # Класс Buffer: сумма каждых 5 подряд идущих чисел
│       │   └── tags_in_songs/                       # Теги‑метаданные для категоризации и поиска объектов
│       ├── crypto_world/                            # Криптовалюты
│       │   ├── inter_exchange_arbitrage_bot/        # FastAPI + aiogram v3, CCXT (Binance/Bybit/OKX/KuCoin/YoBit), AI-анализ новостей
│       │   └── yobit_bot/                           # Торговый бот YoBit: Docker, SQLAlchemy ORM, Alembic
│       ├── CSV_JSON_text_file_formats/              # Анализ структурированных форматов
│       │   └── find_out_the_type_of_crime_that_was_recorded_the_maximum_number_of_times/ # Датасет преступлений Чикаго 2001–н.в.
│       ├── django/                                  # Веб‑приложения на Django
│       │   ├── backend/                             # Блог/CMS: авторизация, CKEditor, Docker, Redis, Nginx
│       │   ├── book_shop/                           # Книжный интернет‑магазин с корзиной (в разработке)
│       │   ├── buy_online_hub/                      # Структура Django-проекта: goods, main, users
│       │   ├── cinema_guide/                        # Кинопортал с жанровыми фильтрами и оценками
│       │   ├── money_convert_django/                # Конвертер валют с моделью ConversionHistory
│       │   ├── portfolio_master/                    # Сайт-портфолио разработчика
│       │   ├── sitewomen/                           # Django-портал с ORM и медиафайлами
│       │   └── zodiac_portal/                       # Гороскопы с динамическим роутингом URL
│       ├── encrypt_and_decrypt/                     # Криптография и безопасность
│       │   ├── creation_and_storage_of_logins_and_passwords/ # SQLite-менеджер паролей (класс BD)
│       │   ├── encrypt_and_decrypt_PDF_file/        # Шифрование/дешифрование PDF с паролем
│       │   ├── encrypt_and_decrypt_all_files_in_directories_pyAesCrypt/ # Рекурсивное AES-256, сохранение .crp
│       │   └── messages_to_images_and_back/         # Стеганография + шифрование в пикселях PNG
│       ├── fast_api/                                # Веб‑сервисы на FastAPI
│       │   ├── fast_api_post_manager/               # CRUD публикаций: Pydantic, SQLAlchemy, Alembic
│       │   ├── lang_chain_fast_summarizer/          # FastAPI + LangChain → суммаризация через LLM
│       │   ├── quick_start_in_fastapi_python/       # 8 учебных микросервисов (auth, files, поиск, регистрация…)
│       │   └── restful_text_processing_with_nltk/   # Токенизация, стемминг, частотный анализ через NLTK
│       ├── flask/                                   # Веб‑приложения на Flask
│       │   ├── flask_database/                      # SQLAlchemy ORM с поддержкой миграций
│       │   ├── integration_telegram_planfix/        # Вебхук: синхронизация Telegram ↔ CRM Planfix
│       │   ├── secure_hub/                          # Авторизация, сессии и защита роутов
│       │   └── website_page_templates/              # Наследование Jinja2-шаблонов, обработка 404/500
│       ├── grpc/                                    # gRPC‑сервисы на Python
│       │   ├── bidirectional_streaming_chat_service/ # Двунаправленный потоковый чат
│       │   ├── book_shop_grpc/                      # Каталог книг с поиском на gRPC вместо REST
│       │   ├── client_streaming_average_calculator/ # Поток чисел от клиента → среднее значение
│       │   ├── grpc_example/                        # Hello World: компиляция .proto → Python-классы
│       │   ├── streaming_grpc_string_analyzer/      # Server streaming: порционный анализ строки
│       │   └── unary_grpc_calculator/               # Синхронный калькулятор (+, -, *, /) Unary RPC
│       ├── ip/                                      # Сетевые данные
│       │   └── getting_information_by_ip/           # ip-api.com: ISP/страна/координаты + карта folium
│       ├── photo/                                   # Обработка изображений
│       │   ├── adding_text_to_photo/                # PIL: текст в заданных координатах, автоопределение шрифта
│       │   └── text_from_image_using_tesseract/     # OCR: выбор языка/файла, pytesseract
│       ├── pyplot_graphics/                         # Научная визуализация (Matplotlib)
│       │   ├── sin_function_plot_0_to_10/           # sin(x) на [0,10] с шагом 0.01 → sin.png
│       │   └── trigonometric_plot.py                # sin + cos с разными стилями → trigan.png
│       ├── scraper/                                 # Веб‑скрапинг
│       │   ├── Instagram_scraper_instaloader/       # Асинхронный сбор данных профилей Instagram
│       │   ├── business_web_scraper/                # Selenium: объявления «бизнес» + извлечение телефонов
│       │   ├── requests_and_beautiful_soup/         # sync_scraper + thread_scraper (lego)
│       │   ├── scrapy/scraper_spider/               # Scrapy: books.toscrape.com с обходом пагинации
│       │   ├── selenium/                            # Автоматизация входа на защищённые сайты
│       │   └── stepic/                              # 7 задач XML/HTML: OSM, Wikipedia, таблицы
│       ├── spreadsheets/                            # Электронные таблицы
│       │   ├── calculation_of_total_caloric_content_work_with_two_sheets/ # КБЖУ из двух листов, запятая-разделитель
│       │   ├── count_four_numbers_for_each_day/     # Меню повара: КБЖУ по дням через openpyxl
│       │   ├── excel_phonebook_parser/              # aiogram 3.3.0 эхо-бот + парсинг Excel телефонной книги
│       │   ├── finding_the_smallest_value/          # Минимум в столбце C из tab.xlsx
│       │   ├── recover_payroll_from_payroll_records/ # «Рога и Копыта»: восстановление ведомости из ZIP
│       │   ├── sample_of_the_highest_average_salary/ # Регион с наибольшей медианной зарплатой
│       │   ├── sort_by_product_name/                # Сортировка продуктовой таблицы по алфавиту
│       │   └── work_with_Pandas/                    # DataFrame, фильтрация, группировка
│       ├── text/                                    # Анализ текста
│       │   ├── fontman/                             # Замена шрифта .docx на рукописный
│       │   └── summarization_of_texts/              # TextRank: лемматизация, сходство предложений, ранжирование
│       ├── video_generation/                        # Мультимедиа
│       │   └── short_video_generation/              # moviepy + YAML-конфиг → Reels/Shorts
│       └── web/                                     # Системные веб‑утилиты
│           ├── dns_proxy_blacklist/                 # DNS-прокси: blacklist + upstream из конфиг-файла
│           └── net_port_scanner/                    # asyncio-сканер, поддержка всех интерфейсов
│
├── solana-webwallet/                                # ⭐ Telegram‑бот для кошельков Solana (Python, Middle)
└── tasks/                                           # 🗂️ Коллекция прикладных и коммерческих проектов (Python)
    ├── auto_ria_tracker/                            # 🚗 AUTO.RIA Toyota Monitor Bot: новые объявления, цены, продажи
    ├── date_assistant/                              # 🤖 AI‑ассистент анализа Instagram-профилей (FastAPI, LLM)
    ├── email_blast/                                 # 📧 Персонализированная рассылка, батчи по 10 000 писем из CSV
    ├── email_sorter_pro/                            # 🔍 Сортировка 200 ГБ баз email по странам, неизвестные → OTHER
    ├── fat32_disk_emulation/                        # 💾 FAT32-диск 20 МБ, команды dir/cd/mkdir/create/cat/rename
    ├── guess_the_card_game/                         # 🃏 6 попыток: угадай цвет/масть/номинал карты
    ├── human_body_mass_index/                       # ⚖️ ИМТ по ВОЗ: 5 категорий (Underweight → Obese)
    ├── numeric_data_file_analyzer/                  # 📊 Max, min, медиана, среднее + длиннейшие последовательности
    ├── order-management-service/                    # 📦 K2 ERP: Клієнт/Товар/Замовлення, DRF, TypeScript, Docker
    ├── scraper/artikul_price_tracker/               # 🛒 Трекер цен Wildberries по артикулам (Selenium + openpyxl)
    └── task_manager/                                # 📋 Django + HTMX: проекты, задачи, дедлайны, Docker
```

---

## 📄 Подробное описание проектов и разделов

### 1. Самостоятельные репозитории (основной профиль)

#### `solana-webwallet`
- **Описание:** Telegram-бот на `aiogram` — некастодиальный кошелёк Solana прямо в чате.
- **Функции:** генерация/импорт кошельков (мнемоника), хранение ключей, баланс SOL, отправка/приём токенов, история транзакций.
- **Реализация:** слои `handlers`, `keyboards`, `external_services` (RPC к Solana), `database`. Docker-контейнер.

#### `tasks`
- **Описание:** Коллекция коммерческих заказов, инструментов автоматизации и прикладных задач.
- **Реализация:**
  - `auto_ria_tracker` — «AUTO.RIA Toyota Monitor Bot»: мониторинг новых объявлений, снижений цен и продаж Toyota. По таймеру парсит HTML, сравнивает с SQLite, уведомляет через aiogram v3. 13 скриншотов в README.
  - `date_assistant` — AI-ассистент: анализ публичных Instagram-профилей → персонализированные рекомендации через LLM (OpenAI, Claude, DeepSeek). Streaming, модульная архитектура провайдеров.
  - `email_blast` — персонализированная email-рассылка с ссылкой, батчи по 10 000 писем из CSV, логирование статусов.
  - `email_sorter_pro` — сортировка до 200 ГБ баз email по странам через гибкий конфиг с правилами доменных зон. Неизвестные домены → OTHER.
  - `fat32_disk_emulation` — эмулятор FAT32-диска (20 МБ). Поддерживаемые команды: `dir`, `cd`, `mkdir`, `create`, `cat`, `rename`.
  - `guess_the_card_game` — 6 попыток на каждый тип вопроса (цвет/масть/номинал/оба) из 52-карточной колоды.
  - `human_body_mass_index` — калькулятор ИМТ: 5 категорий по ВОЗ (Underweight, Normal, Overweight, Obese I/II).
  - `numeric_data_file_analyzer` — 6 значений из файла с целыми числами: max, min, медиана, среднее + наидлиннейшие возрастающая и убывающая последовательности.
  - `order-management-service` — K2 ERP (модуль обліку замовлень): сутності Клієнт/Товар/Замовлення через OrderItem, REST API на DRF, TypeScript-форми, Docker, Swagger/ReDoc, pytest.
  - `scraper/artikul_price_tracker` — трекер цен товаров Wildberries по артикулам: Selenium для обхода сайта, Excel-отчёты через openpyxl.
  - `task_manager` — Django + HTMX: управление проектами и задачами с дедлайнами без перезагрузки страницы. Docker dev/prod (Nginx, PostgreSQL), pre-commit, линтинг.

---

### 2. Раздел educationalProjects / C

#### `Linux_kernel_modules`
- `hello-1..5` — жизненный цикл LKM на Ubuntu 23.10: `module_init()`, `module_exit()`, `module_param()`, метаданные.
- `chardev/character_driver_for_tracking_reads` — драйвер с счётчиком чтений файла.
- `chardev/ioctl` — драйвер устройства с поддержкой ioctl.
- `proc/proc-1..4` — четыре варианта работы с `/proc` (от простого к seq_file).
- `sysfs/hello-sysfs` — экспорт параметров через sysfs.
- `simple_hello` — компиляция через GCC, отладка через strace.

#### `UNIX_Professionalnoe_programmirovanie_3-e_izd_2018`
- `directory_file_listing` — аналог `ls` через `opendir()` / `readdir()` с форматированным выводом метаданных.

#### `network_programming`
- `getaddrinfo_example` — DNS-разрешение имён в IPv4/IPv6 через структуру `addrinfo`.
- `reverse_socks5_proxy` — обратный SOCKS5-прокси: клиент инициирует соединение изнутри защищённой сети.
- `unix_network_development_applications`:
  - `Time_and_Date_TCP_Client_and_Simple_Time_and_Date_Server` — TCP-сервер времени + клиент IPv4/IPv6.
  - `pieces_of_code_for_network_programming` — 4 подпапки: определение порядка байтов, конвертация host↔network, функции `inet_aton`/`inet_ntoa`/`inet_pton`, группы `b*` и `mem*`.
  - `UNIX_Network_Development_3rd_Edition/unpv13e` — исходный код книги Стивенса UNP: TCP/UDP серверы, `select`/`poll`/`epoll`, `ping`, `traceroute`.

#### `solutions_to_C_book_Exercises_Kernighan_Ritchie_3rd_Edition`
17 упражнений K&R (глава 1): `1.6–1.7` (EOF/getchar), `1.8` (счётчики), `1.9` (пробелы), `1.10` (escape), `1.11` (слова), `1.12` (по слову в строке), `1.13–1.14` (гистограммы), `1.15` (конвертер температур), `1.16` (длинные строки), `1.17–1.22` (detab, entab, реверс, разбиение).

---

### 3. Раздел educationalProjects / C++

#### `TCPCommunication`
TCP клиент-сервер на BSD-сокетах C++: `TCP Server` ожидает входящие подключения, `TCPClient` отправляет текстовые пакеты.

#### `algorithms/sorting`
4 варианта: пузырьковая (прямой/обратный порядок, с флагом), сортировка вставками с замером времени, QuickSort.

#### `arrays/working_with_dynamic_arrays`
`dynamic_array_copy` — копирование динамического массива с инициализацией через `random_device` и `mt19937`.

#### `class`
- `class_singly_linked_list` — Node + List без STL: добавление, удаление, поиск.
- `class_string` — кастомный класс на `char*`: управление памятью, конструктор копирования.
- `decorator_coffee_consol` — паттерн «Декоратор»: гибкий расчёт стоимости кофейных заказов.
- `duck` — паттерн «Стратегия»: динамическая смена поведения (полёт, кряканье) во время выполнения.
- `map_and_multimap` — `std::map` и `std::multimap`: хранение пар ключ-значение.
- `matrix` — перегрузка `[]`, `+`, `*`, `<<`.
- `rectangle` — «Правило трёх»: деструктор, конструктор копирования, `operator=`.
- `stack_calculator` — стековый калькулятор.
- `stack_data_structure` — стек LIFO: `push()`, `pop()`, `top()`, `isEmpty()`.
- `tasks/odd_numbers_to_beginning_even_numbers_to_end_array` — перемещение нечётных в начало, чётных в конец вектора.

#### `dynamic_programming`
- `counting_trajectories_from_city_to_city` — уникальные пути в ориентированном ациклическом графе.
- `digital_herringbone` — числовой паттерн «ёлочка» в двумерной структуре.

#### `lafore_task`
- `3.1–3.4` — базовые конструкции: циклы, структуры данных, простые классы.
- `chapter_4`: `4.1` (перегрузка операторов), `4.3` (константные методы), `card_game`, `english_system_of_measures` / `english_system_of_measures2`, `word_count`.
- `chapter_7`: `7.1` (виртуальные методы), `7.2` (абстрактные базовые классы).

#### `struct`
- `queue` — кольцевая очередь FIFO с динамической памятью.
- `students_name_and_grades` — карточка студента: ФИО, предметы, оценки, валидация.

#### `tasks/array_tasks`
- `array_elements_increase_divide_by_first_element_decrease_by_number` — обработка элементов массива.
- `fill_0_1_2_3_4...and..._3_2_1_0` — заполнение массива по паттерну.
- `finding_the_mode_of_a_number` — поиск моды.
- `search_element_index` — поиск индекса элемента.

#### `tasks/various_tasks`
- `algorithm_of_lexicographic_sorting` — лексикографическая сортировка строк.
- `find_the_number_of_times_the_light_is_turned_on` — подсчёт включений света.
- `output_current_date` — вывод текущей даты.
- `parentheses/stack_parentheses` — валидатор баланса круглых/фигурных скобок через стек.
- `simple_tasks` — min/max 4 чисел, округление, сортировка 3 чисел, произведение цифр, суммы последовательностей.
- `triangle_check` — проверка возможности построения треугольника.

---

### 4. Раздел educationalProjects / Python

#### `ai`
- `generating_images_from_text_OpenAI_and_ChatGPT` — `openai.Image.create()`: описание → изображение → диск + JSON-лог.
- `web_crawler_ads_generator` — `cloudscraper` → OpenAI summary → CSV с объявлениями для Google Ads (1 на страницу).

#### `api`
- `email_email_checking_and_verification_hunter` — клиент Hunter.io: 2-3 endpoint, валидация email, сохранение в локальной переменной.
- `getting_access_token_to_artsynet_API_and_sorting` — OAuth Artsy.net: имя + год рождения художников по ID, сортировка по рейтингу.
- `hunter_check_mail` — расширенный Hunter.io: SQLite, меню, утилиты, пакетная проверка по домену.
- `numbers_api_explorer` — интерактивное меню запросов к `numbersapi.com` (math/trivia/date).

#### `audio_and_text`
- `add_words_and_music` — выбор источника текста (файл или клавиатура) → TTS → наложение на музыку.
- `convert_text_to_speech_in_python` — TTS через `lovoai` API с настройкой параметров.
- `speech_to_text_library_speech_recognition` — запись с микрофона (выбор качества/частоты/языка) + SpeechRecognition.
- `transcription_of_text_from_an_audio_file` — Whisper tiny/base/medium/large с описанием возможностей каждой модели.

#### `BD/SQLite`
- `aggregation_and_grouping` — `COUNT`, `DISTINCT`, `GROUP BY`, `HAVING` с теоретическими объяснениями.
- `commands_when_work_with_tables` — таблица `users`, CRUD через context manager.
- `first_steps_with_SQLite` — подключение, создание таблиц, генерация данных, запросы.

#### `black_hat_python`
- `my_netcat` — TCP: соединение, прослушивание портов, многопоточная обработка, удалённый шелл.
- `scan` — ARP/ICMP-сканер хостов в подсети.
- `tcp_client` — `simple_tcp_client.py` и расширенный вариант с логированием.
- `tcp_proxy` — перехват трафика с `hexdump` форматированием, модификация на лету.
- `tcp_server` — `AF_INET` + `SOCK_STREAM`, каждое соединение в отдельном потоке.
- `udp_client` — `AF_INET` + `SOCK_DGRAM`, отправка и приём ответа.

#### `bots / aiogram_2`
- `ai_checklist_guardian` — выбор из 5 локаций → пошаговый чеклист через OpenAI (aiogram v2.25).
- `telegram_bot` — архитектурный пример с хендлерами, клавиатурами и БД.
- `telegram_bot_inline` — inline-кнопки и обработка callback-запросов.

#### `bots / aiogram_3`
- `bot_guess_the_number` / `bot_guess_the_number_dictionary` — «Угадай число» с SQLite и in-memory хранилищем.
- `bot_rock_paper_scissors` — «Камень-ножницы-бумага» с Pydantic-конфигурацией.
- `callback_data_factory` — типизированные callback через Callback Data Factory.
- `edit_messages` — 3 способа редактирования сообщений.
- `editing_messages_of_different_types` — `edit_message_media` для замены типов медиафайлов.
- `form_filling_bot_fsm` — FSM-анкета с диаграммой состояний.
- `formatting_text_in_messages` — HTML, Markdown, кастомные сущности Telegram.
- `improved_echo_bot` — валидация типов контента (текст, стикеры, голосовые, файлы).
- `inline_buttons` — URL-кнопки и базовые callback.
- `inline_callback_buttons` — расширенные callback-кнопки с медиафайлами и изображениями.
- `middleware_example_bot` — logging, throttling, проверка прав доступа.
- `naval_combat_game` — «Морской бой» на inline 8×8 сетке + FSM + SQLite.
- `own_keyboard_generator` — функция `create_inline_kb` с произвольным числом кнопок в строке.
- `regular_buttons_telegram_bot` / `simple_echo_bot` — базовые примеры.
- `telegram_bot_book` — чтение книг с пагинацией и сохранением закладки в БД.
- `telegram_bot_menu_button` — `set_my_commands`, кастомизация кнопки Web App.

#### `bots / Другие`
- `kitties_bot` — случайные фото кошек/собак через публичные API.
- `telegram_bot_project_skeleton` — boilerplate: структура папок, `.env`, базовые команды.
- `youTube_video_search_bot` — `aiohttp` + YouTube Data API v3.

#### `class`
- `Is_the_class_an_ancestor` — определение предков/потомков обходом графа иерархии классов.
- `MoneyBox_for_working_with_a_virtual_piggy_bank` — копилка с контролем вместимости (целое число монет).
- `analogue_of_a_money_wallet` — кошелёк: валюта (3 заглавных буквы), баланс, пополнение, списание, конвертация.
- `class_Transport` — полиморфизм: `Transport` → `Car`, `Boat`, `Plane`.
- `class_filter` — мультифильтр (несколько функций-предикатов) через протокол итератора.
- `class_that_implements_an_iterator` — `RandomIterator`: каждый `__next__()` возвращает случайное число.
- `create_class_Newlnt_inherited_from_int` — расширение `int` методом `repeat(n)`.
- `implementation_of_PositiveList_class` — список с `NonPositiveError` при вставке ≤ 0.
- `information_logging` — миксин `Loggable` для автологирования вызовов методов.
- `people_with_a_sweet_tooth_vegetarians_meat_lovers` — классификация предпочтений по опросу Днепр 2020.
- `stack_implementation` — расширенный стек с арифметическими операциями (+, -, *, //) над двумя вершинами.
- `sum_of_the_first_five_numbers` — класс `Buffer`: накапливает числа и печатает сумму каждых 5 подряд.
- `tags_in_songs` — теги-метаданные для категоризации объектов и ускорения поиска.

#### `crypto_world`
- `inter_exchange_arbitrage_bot` — FastAPI + aiogram v3 + CCXT (Binance/Bybit/OKX/KuCoin/YoBit): поиск арбитражных окон на споте, AI-анализ новостного фона.
- `yobit_bot` — автоматическая торговля на YoBit: Docker, SQLAlchemy ORM, Alembic-миграции, история транзакций.

#### `CSV_JSON_text_file_formats`
- `find_out_the_type_of_crime_that_was_recorded_the_maximum_number_of_times` — датасет преступлений Чикаго 2001–н.в.: наиболее частый тип в 2015 году через CSV/JSON.

#### `django`
- `backend` — блог с авторизацией, комментариями, тегами, CKEditor, Docker, Redis, Nginx.
- `book_shop` — книжный интернет-магазин (в разработке).
- `buy_online_hub` — структура Django-проекта: приложения goods, main, users.
- `cinema_guide` — кинопортал с жанровыми фильтрами и пользовательскими оценками.
- `money_convert_django` — конвертер валют с моделью `ConversionHistory`.
- `portfolio_master` — сайт-портфолио для демонстрации навыков и проектов.
- `sitewomen` — Django-портал с ORM, кастомными тегами шаблонизатора и медиафайлами.
- `zodiac_portal` — гороскопы с динамическим роутингом URL.

#### `encrypt_and_decrypt`
- `creation_and_storage_of_logins_and_passwords` — класс `BD`: SQLite с методами CRUD для логинов/паролей.
- `encrypt_and_decrypt_PDF_file` — консольная утилита: шифрование/дешифрование PDF с паролем.
- `encrypt_and_decrypt_all_files_in_directories_pyAesCrypt` — рекурсивное AES-256 шифрование, сохранение `.crp`, удаление оригиналов.
- `messages_to_images_and_back` — стеганография + шифрование: скрытие текста в пикселях PNG.

#### `fast_api`
- `fast_api_post_manager` — CRUD публикаций: Pydantic-валидация, SQLAlchemy, Alembic-миграции.
- `lang_chain_fast_summarizer` — FastAPI + LangChain: суммаризация длинных текстов через LLM.
- `quick_start_in_fastapi_python` — 8 учебных микросервисов: cookie-аутентификация, поиск продуктов, файловый сервер, обратная связь, суммирование, верификация возраста, регистрация пользователей.
- `restful_text_processing_with_nltk` — токенизация, стемминг, частотный анализ через NLTK.

#### `flask`
- `flask_database` — SQLAlchemy ORM с поддержкой миграций.
- `integration_telegram_planfix` — вебхук: двусторонняя синхронизация Telegram ↔ CRM Planfix.
- `secure_hub` — авторизация, сессии, защита роутов от неавторизованных пользователей.
- `website_page_templates` — наследование Jinja2-шаблонов, обработка ошибок 404/500.

#### `grpc`
- `unary_grpc_calculator` — синхронный калькулятор (+, -, *, /) Unary RPC.
- `client_streaming_average_calculator` — поток чисел от клиента → среднее после закрытия потока.
- `bidirectional_streaming_chat_service` — двунаправленный потоковый чат в реальном времени.
- `streaming_grpc_string_analyzer` — Server streaming: сервер анализирует строку и возвращает результаты порциями.
- `book_shop_grpc` — каталог книг с поиском и управлением заказами на gRPC вместо REST.
- `grpc_example` — Hello World: компиляция `.proto` файлов в Python-классы.

#### `ip`
- `getting_information_by_ip` — GET к `ip-api.com`: ISP, страна, город, координаты + интерактивная карта `folium`.

#### `photo`
- `adding_text_to_photo` — PIL: добавление текста в заданных координатах, автоопределение шрифта по ОС.
- `text_from_image_using_tesseract` — OCR: выбор языка и файла/группы файлов через pytesseract.

#### `pyplot_graphics`
- `sin_function_plot_0_to_10` — sin(x) на [0, 10] с шагом 0.01, сохранение в `sin.png`.
- `trigonometric_plot.py` — sin + cos с разными стилями линий, сохранение в `trigan.png`.

#### `scraper`
- `Instagram_scraper_instaloader` — асинхронный сбор данных профилей: посты, подписчики.
- `business_web_scraper` — Selenium: объявления категории «бизнес» + извлечение телефонов.
- `requests_and_beautiful_soup` — `sync_scraper` и многопоточный `thread_scraper` для lego-каталогов.
- `scrapy/scraper_spider` — Scrapy: books.toscrape.com с автоматическим обходом пагинации.
- `selenium` — автоматизация входа на защищённые сайты через `loging.py`.
- `stepic` — 7 задач XML/HTML: OSM-карты, Wikipedia, таблицы, подсчёт тегов.

#### `spreadsheets`
- `calculation_of_total_caloric_content_work_with_two_sheets` — задача Васи-квартирмейстера: КБЖУ из двух листов, запятая как разделитель дробной части.
- `count_four_numbers_for_each_day` — меню повара: КБЖУ по дням через openpyxl.
- `excel_phonebook_parser` — aiogram 3.3.0 эхо-бот + парсинг телефонной книги из Excel.
- `finding_the_smallest_value` — минимум в столбце C из `tab.xlsx`.
- `recover_payroll_from_payroll_records` — задача «Рога и Копыта»: восстановление ведомости из ZIP-архива Stepik.
- `sample_of_the_highest_average_salary` — регион с наибольшей **медианной** зарплатой по профессиям.
- `sort_by_product_name` — сортировка продуктовой таблицы по алфавиту.
- `work_with_Pandas` — создание DataFrame, фильтрация строк, группировка данных.

#### `text`
- `fontman` — замена шрифта `.docx` на рукописный с сохранением форматирования.
- `summarization_of_texts` — TextRank: лемматизация, матрица сходства предложений, ранжирование.

#### `video_generation`
- `short_video_generation` — moviepy + YAML-конфиг: Reels/Shorts из изображений и аудиодорожек.

#### `web`
- `dns_proxy_blacklist` — DNS-прокси: blacklist доменов и адрес upstream в конфиг-файле.
- `net_port_scanner` — asyncio-сканер TCP-портов, поддержка всех сетевых интерфейсов если хост не указан.

---

## ⚠️ Проекты без README (нужно создать)

```
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
  python/django/book_shop/           (только "В процессе")
  python/django/cinema_guide/
  python/django/portfolio_master/
  python/django/sitewomen/
  python/fast_api/fast_api_post_manager/     (пустой)
  python/fast_api/lang_chain_fast_summarizer/
  python/flask/secure_hub/
  python/grpc/book_shop_grpc/        (пустой)
  python/grpc/grpc_example/
  python/scraper/scrapy/
  python/black_hat_python/scan/
  python/video_generation/short_video_generation/
  python/text/fontman/

tasks:
  tasks/date_assistant/              (пустой)
  tasks/scraper/artikul_price_tracker/
```
