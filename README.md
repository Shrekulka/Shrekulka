# 📚 Shrekulka — Developer Portfolio & Projects

Welcome to the structured project repository of developer **Shrekulka**. This space compiles commercial software, custom business tools, and an educational portfolio. It showcases practical systems programming in **C/C++**, web development, asynchronous Telegram bots, system integrations, and automation scripts developed in **Python**.

---

## 🌳 Repository Structure

    Shrekulka/
    │
    ├── educationalProjects/                             # 📚 Main Educational Portfolio (Python, C, C++)
    │   ├── c/                                           # Projects in C (System and Network Programming)
    │   │   ├── Linux_kernel_modules/                    # Loadable Kernel Modules (LKM) Development
    │   │   │   └── develop/kernel/                      # hello-1..5, chardev, ioctl, proc-1..4, sysfs, simple_hello
    │   │   ├── UNIX_Professionalnoe_programmirovanie_3-e_izd_2018/ # Exercises from W. Richard Stevens' APUE Book
    │   │   │   └── directory_file_listing/              # Custom ls utility using opendir() / readdir()
    │   │   ├── network_programming/                     # Network Applications and Protocols in C
    │   │   │   ├── getaddrinfo_example/                 # Domain Name System (DNS) host resolution (IPv4/IPv6) via getaddrinfo
    │   │   │   ├── reverse_socks5_proxy/                # Reverse SOCKS5 Proxy Implementation
    │   │   │   └── unix_network_development_applications/ # Code patterns from W. Richard Stevens' UNP Book
    │   │   │       ├── Time_and_Date_TCP_Client_and_Simple_Time_and_Date_Server/ # TCP Time Server and Client (IPv4/IPv6)
    │   │   │       └── pieces_of_code_for_network_programming/ # Byte order checks, IP conversions (4 subfolders)
    │   │   └── solutions_to_C_book_Exercises_Kernighan_Ritchie_3rd_Edition/ # 17 Exercises from Kernighan & Ritchie (1.6–1.22)
    │   │
    │   ├── c++/                                         # Projects in C++ (Algorithms, Object-Oriented Programming, Networking)
    │   │   ├── TCPCommunication/                        # TCP Client-Server application using BSD sockets
    │   │   │   ├── TCP Server/                          # Server Side
    │   │   │   └── TCPClient/                           # Client Side
    │   │   ├── algorithms/                              # Fundamental Algorithms
    │   │   │   ├── reverse_algorithm/                   # Reversing vectors via Standard Template Library (STL) iterators
    │   │   │   └── sorting/                             # 4 Sorting Variations
    │   │   │       ├── bubble_sort/bubble sort in reverse order/          # Bubble sort in descending order
    │   │   │       ├── bubble_sort/bubble_sort_from_start_to_end_of_array/ # Bubble sort in ascending order
    │   │   │       ├── bubble_sort/flag_bubble_sort/                      # Optimized bubble sort using modification flags
    │   │   │       ├── insertion_sort_algorithm_and_execution_time/       # Insertion sort with execution time profiling
    │   │   │       └── quick_sort/                                        # Quicksort
    │   │   ├── arrays/                                  # Array and Vector Manipulation
    │   │   │   ├── array_shuffling/                     # Shuffling with mathematical distribution verification
    │   │   │   ├── max_number_in_array/                 # Finding maximum value via hardware Random Number Generator (random_device)
    │   │   │   ├── output_array_in_ascending_order/     # Bubble sort ordering
    │   │   │   ├── unique_random_numbers_in_an_array/   # Generating unique integers using std::set
    │   │   │   └── working_with_dynamic_arrays/         # Manual memory management: new[], copy, delete[]
    │   │   │       └── dynamic_array_copy/              # Copying dynamic arrays with mt19937 engine
    │   │   ├── class/                                   # Object-Oriented Programming in C++
    │   │   │   ├── class_singly_linked_list/            # Custom singly linked list class without STL
    │   │   │   ├── class_string/                        # Custom string manager operating on char*
    │   │   │   ├── decorator_coffee_consol/             # Decorator design pattern for coffee ordering
    │   │   │   ├── duck/                                # Strategy design pattern
    │   │   │   ├── map_and_multimap/                    # Core use cases of std::map and std::multimap
    │   │   │   ├── matrix/                              # Matrix class with overloaded [], +, *, and << operators
    │   │   │   ├── rectangle/                           # Rule of Three: copy constructor, operator=, and destructor
    │   │   │   ├── stack_calculator/                    # Stack-based expression evaluator
    │   │   │   ├── stack_data_structure/                # LIFO stack implementation: push(), pop(), top(), isEmpty()
    │   │   │   └── tasks/                               # Supplemental class design exercises
    │   │   │       └── odd_numbers_to_beginning_even_numbers_to_end_array/ # Sorting odd values to the front, even to the rear
    │   │   ├── dynamic_programming/                     # Dynamic Programming Concepts
    │   │   │   ├── counting_trajectories_from_city_to_city/ # Unique path calculation in Directed Acyclic Graphs (DAG)
    │   │   │   └── digital_herringbone/                 # Herringbone search pattern in two-dimensional numeric layouts
    │   │   ├── lafore_task/                             # Practice tasks from Robert Lafore's Object-Oriented Programming book
    │   │   │   ├── 3.1/ 3.2/ 3.3/ 3.4/                 # Fundamental class structures and member methods
    │   │   │   ├── chapter_4/                           # Operator overloading and custom copy constructors
    │   │   │   │   ├── 4.1/                             # Basic operator overloading
    │   │   │   │   ├── 4.3/                             # Constant methods
    │   │   │   │   ├── card_game/                       # Interactive card game with overloaded operators
    │   │   │   │   ├── english_system_of_measures/      # Imperial measurement calculations
    │   │   │   │   ├── english_system_of_measures2/     # Expanded imperial metrics conversion
    │   │   │   │   └── word_count/                      # Stream analyzer counting unique words
    │   │   │   └── chapter_7/                           # Runtime polymorphism and virtual methods
    │   │   │       ├── 7.1/                             # Virtual function dispatch mechanisms
    │   │   │       └── 7.2/                             # Abstract base classes and pure virtual methods
    │   │   ├── struct/                                  # Composite Data Types
    │   │   │   ├── queue/                               # Circular FIFO queue using dynamic memory allocation
    │   │   │   └── students_name_and_grades/            # Student record card validating strings and grade levels
    │   │   └── tasks/                                   # Educational C++ Challenges
    │   │       ├── array_tasks/                         # Array manipulation challenges
    │   │       │   ├── array_elements_increase_divide_by_first_element_decrease_by_number/
    │   │       │   ├── fill_0_1_2_3_4...and..._3_2_1_0/
    │   │       │   ├── finding_the_mode_of_a_number/
    │   │       │   └── search_element_index/
    │   │       └── various_tasks/                       # Miscellaneous C++ challenges
    │   │           ├── algorithm_of_lexicographic_sorting/ # Lexicographical sorting of strings
    │   │           ├── find_the_number_of_times_the_light_is_turned_on/ # State tracking calculations
    │   │           ├── output_current_date/             # Printing standard system date
    │   │           ├── parentheses/stack_parentheses/   # Bracket validation utilizing LIFO stack
    │   │           ├── simple_tasks/                    # Basic tasks (min/max, rounding, sorting, sums)
    │   │           └── triangle_check/                  # Triangle inequality validator
    │   │
    │   └── python/                                      # Main Python Development Section
    │       ├── ai/                                      # Artificial Intelligence Integrations
    │       │   ├── generating_images_from_text_OpenAI_and_ChatGPT/ # OpenAI DALL-E Application Programming Interface (API), local saving, JSON logging
    │       │   └── web_crawler_ads_generator/           # cloudscraper → OpenAI summary → CSV format for Google Ads
    │       ├── api/                                     # Interaction with External Web APIs
    │       │   ├── email_email_checking_and_verification_hunter/ # Hunter.io client, email validation
    │       │   ├── getting_access_token_to_artsynet_API_and_sorting/ # OAuth 2.0 flow with Artsy.net, sorting artists by timeline
    │       │   ├── hunter_check_mail/                   # Advanced Hunter.io checker with local SQLite databases and terminal interface
    │       │   └── numbers_api_explorer/                # Request interface for numbersapi.com (math, trivia, and date facts)
    │       ├── audio_and_text/                          # Voice and Audio Processing
    │       │   ├── add_words_and_music/                 # TTS engine + audio overlays with selectable text inputs
    │       │   ├── convert_text_to_speech_in_python/    # TTS via lovoai API
    │       │   ├── speech_to_text_library_speech_recognition/ # Recording from microphone, language/quality selection
    │       │   └── transcription_of_text_from_an_audio_file/ # Whisper models (tiny, base, medium, large) compared
    │       ├── BD/                                      # Database Engineering and Management
    │       │   └── SQLite/                              # SQLite tasks and configuration templates
    │       │       ├── aggregation_and_grouping/        # COUNT, DISTINCT, GROUP BY, HAVING commands
    │       │       ├── commands_when_work_with_tables/  # CRUD operations utilizing context manager connection wrappers
    │       │       └── first_steps_with_SQLite/         # Connecting, table structures, and manual query executions
    │       ├── black_hat_python/                        # Penetration Testing Scripts from "Black Hat Python"
    │       │   ├── my_netcat/                           # NetCat clone: connection management, listening modes, remote shell
    │       │   ├── scan/                                # ARP and ICMP subnet hosts discovery scanner
    │       │   ├── tcp_client/                          # Simple and advanced TCP client utilities
    │       │   ├── tcp_proxy/                           # Traffic interceptor with hexdump formatting
    │       │   ├── tcp_server/                          # Multithreaded TCP server (AF_INET and SOCK_STREAM)
    │       │   └── udp_client/                          # UDP client (AF_INET and SOCK_DGRAM)
    │       ├── bots/                                    # Telegram bot development
    │       │   ├── aiogram_2/                           # Bots constructed using aiogram version 2
    │       │   │   ├── ai_checklist_guardian/           # Location selection → step-by-step checklist via OpenAI (aiogram v2.25)
    │       │   │   ├── telegram_bot/                    # Modular architectural layout: handlers, keyboards, database connection
    │       │   │   └── telegram_bot_inline/             # Inline keyboards handling dynamic callback data
    │       │   ├── aiogram_3/                           # Bots constructed using aiogram version 3
    │       │   │   ├── bot_guess_the_number/            # "Guess the Number" game tracking users via SQLite databases
    │       │   │   ├── bot_guess_the_number_dictionary/ # "Guess the Number" game storing state in local dictionaries
    │       │   │   ├── bot_rock_paper_scissors/         # Interactive match using Pydantic configuration models
    │       │   │   ├── callback_data_factory/           # Typed callbacks using Callback Data Factories
    │       │   │   ├── edit_messages/                   # Three methods for editing inline text messages
    │       │   │   ├── editing_messages_of_different_types/ # edit_message_media for media swapping
    │       │   │   ├── form_filling_bot_fsm/            # Finite State Machine (FSM) registration questionnaire with state diagrams
    │       │   │   ├── formatting_text_in_messages/     # HTML, Markdown, and custom Telegram entities
    │       │   │   ├── improved_echo_bot/               # Echo bot with content type validation
    │       │   │   ├── inline_buttons/                  # Direct url buttons and simple inline triggers
    │       │   │   ├── inline_callback_buttons/         # Expanded callback buttons with media files
    │       │   │   ├── middleware_example_bot/          # Middlewares for logging, rate-limiting (throttling), and role checks
    │       │   │   ├── naval_combat_game/               # "Naval Combat" game on inline 8x8 grids + FSM + SQLite
    │       │   │   ├── own_keyboard_generator/          # create_inline_kb generator mapping arbitrary button templates
    │       │   │   ├── regular_buttons_telegram_bot/    # Reply keyboard layouts
    │       │   │   ├── simple_echo_bot/                 # Entry-level text echo implementation
    │       │   │   ├── telegram_bot_book/               # Book reading bot containing pagination and persistent bookmark databases
    │       │   │   └── telegram_bot_menu_button/        # Commands via set_my_commands and Web App button integration
    │       │   ├── kitties_bot/                         # Random cat/dog pictures via public APIs
    │       │   ├── telegram_bot_project_skeleton/       # Boilerplate project: file hierarchy, dotenv templates, default commands
    │       │   └── youTube_video_search_bot/            # aiohttp + YouTube Data API v3
    │       ├── class/                                   # Object-Oriented Programming (OOP) in Python
    │       │   ├── Is_the_class_an_ancestor/            # Identifying ancestor/descendant relationships via class graph traversal
    │       │   ├── MoneyBox_for_working_with_a_virtual_piggy_bank/ # Piggy bank with capacity limitations
    │       │   ├── analogue_of_a_money_wallet/          # Wallet: currency codes (3 uppercase letters), balance, and conversion operations
    │       │   ├── class_Transport/                     # Polymorphism: Transport, Car, Boat, Plane classes
    │       │   ├── class_filter/                        # Multifilter — analogue of the built-in filter() function
    │       │   ├── class_that_implements_an_iterator/   # RandomIterator class returning random values via __next__()
    │       │   ├── create_class_Newlnt_inherited_from_int/ # Extending standard int class with repeat(n) method
    │       │   ├── implementation_of_PositiveList_class/ # Custom list throwing NonPositiveError on insertion of values <= 0
    │       │   ├── information_logging/                 # Loggable mixin for automatic method call logging
    │       │   ├── people_with_a_sweet_tooth_vegetarians_meat_lovers/ # Dietary preference classifier (Dnipro 2020 dataset)
    │       │   ├── stack_implementation/                # Extended stack with arithmetic operations (+,-,*,//) on top values
    │       │   ├── sum_of_the_first_five_numbers/       # Buffer class: printing sum of every five consecutive numbers
    │       │   └── tags_in_songs/                       # Tag-based metadata categorization for faster object lookups
    │       ├── crypto_world/                            # Cryptocurrency projects
    │       │   ├── inter_exchange_arbitrage_bot/        # FastAPI + aiogram v3, CCXT integration, AI news analysis
    │       │   └── yobit_bot/                           # YoBit trading bot: Docker, SQLAlchemy ORM, Alembic migrations
    │       ├── CSV_JSON_text_file_formats/              # Parsing structured file formats
    │       │   └── find_out_the_type_of_crime_that_was_recorded_the_maximum_number_of_times/ # Chicago Crimes 2001-Present dataset analysis
    │       ├── django/                                  # Web applications using Django framework
    │       │   ├── backend/                             # Blog/Content Management System: authentication, CKEditor, Docker, Redis, Nginx
    │       │   ├── book_shop/                           # Online bookstore with shopping cart (In development)
    │       │   ├── buy_online_hub/                      # Base Django project structure: goods, main, users applications
    │       │   ├── cinema_guide/                        # Movie portal with genre filters and user ratings
    │       │   ├── money_convert_django/                # Currency converter with ConversionHistory model
    │       │   ├── portfolio_master/                    # Personal portfolio website
    │       │   ├── sitewomen/                           # Django-based portal with advanced ORM and template tags
    │       │   └── zodiac_portal/                       # Horoscopes with dynamic URL routing
    │       ├── encrypt_and_decrypt/                     # Cryptography and security
    │       │   ├── creation_and_storage_of_logins_and_passwords/ # SQLite-based password manager (database class)
    │       │   ├── encrypt_and_decrypt_PDF_file/        # Password-based PDF encryption/decryption command-line tool
    │       │   ├── encrypt_and_decrypt_all_files_in_directories_pyAesCrypt/ # Recursive AES-256 folder encryption to .crp files
    │       │   └── messages_to_images_and_back/         # Steganography + pixel encryption in PNG images
    │       ├── fast_api/                                # Web services on FastAPI
    │       │   ├── fast_api_post_manager/               # CRUD for posts: Pydantic validation, SQLAlchemy, Alembic
    │       │   ├── lang_chain_fast_summarizer/          # FastAPI + LangChain for Large Language Model text summarization
    │       │   ├── quick_start_in_fastapi_python/       # 8 educational microservices (authentication, file servers, search...)
    │       │   └── restful_text_processing_with_nltk/   # Tokenization, stemming, frequency analysis via NLTK
    │       ├── flask/                                   # Web applications on Flask
    │       │   ├── flask_database/                      # SQLAlchemy ORM with migrations support
    │       │   ├── integration_telegram_planfix/        # Webhook: Telegram ↔ Planfix CRM integration
    │       │   ├── secure_hub/                          # Session-based authentication and route protection
    │       │   └── website_page_templates/              # Jinja2 template inheritance, custom 404/500 error pages
    │       ├── grpc/                                    # gRPC services in Python
    │       │   ├── bidirectional_streaming_chat_service/ # Bidirectional streaming chat application
    │       │   ├── book_shop_grpc/                      # Book catalog with gRPC search instead of Representational State Transfer
    │       │   ├── client_streaming_average_calculator/ # Client stream of numbers returning calculated average
    │       │   ├── grpc_example/                        # Hello World: compiling .proto files to Python classes
    │       │   ├── streaming_grpc_string_analyzer/      # Server-side streaming string analyzer
    │       │   └── unary_grpc_calculator/               # Synchronous Unary Remote Procedure Call calculator
    │       ├── ip/                                      # Network utilities
    │       │   └── getting_information_by_ip/           # ip-api.com: ISP/Location details + Folium interactive map
    │       ├── photo/                                   # Image processing
    │       │   ├── adding_text_to_photo/                # Pillow: adding text with OS font detection
    │       │   └── text_from_image_using_tesseract/     # Optical Character Recognition (OCR) via pytesseract
    │       ├── pyplot_graphics/                         # Scientific visualization (Matplotlib)
    │       │   ├── sin_function_plot_0_to_10/           # Plotting sin(x) on interval [0,10] with step 0.01
    │       │   └── trigonometric_plot.py                # Combined sine/cosine plot with different line styles
    │       ├── scraper/                                 # Web scraping tools
    │       │   ├── Instagram_scraper_instaloader/       # Asynchronous gathering of Instagram profile details
    │       │   ├── business_web_scraper/                # Selenium parser for business category listings and phone numbers
    │       │   ├── requests_and_beautiful_soup/         # Synchronous and multithreaded web scrapers for catalog items
    │       │   ├── scrapy/scraper_spider/               # Scrapy spider with pagination navigation on books.toscrape.com
    │       │   ├── selenium/                            # Automated login script for secure websites
    │       │   └── stepic/                              # 7 XML/HTML tasks: OpenStreetMap data, Wikipedia parsing, table extraction
    │       ├── spreadsheets/                            # Spreadsheet parsing and processing
    │       │   ├── calculation_of_total_caloric_content_work_with_two_sheets/ # Calorie tracking spanning two sheets with comma separators
    │       │   ├── count_four_numbers_for_each_day/     # Daily calorie breakdown calculation via openpyxl
    │       │   ├── excel_phonebook_parser/              # aiogram v3.3.0 bot parsing telephone contacts from Excel
    │       │   ├── finding_the_smallest_value/          # Finding the minimum value in specific Excel columns
    │       │   ├── recover_payroll_from_payroll_records/ # Stepik challenge: reconstructing payroll registries from ZIP archives
    │       │   ├── sample_of_the_highest_average_salary/ # Analysis of regional median salaries
    │       │   ├── sort_by_product_name/                # Sorting tables alphabetically
    │       │   └── work_with_Pandas/                    # DataFrame manipulation, filtering, and grouping
    │       ├── text/                                    # Text analysis
    │       │   ├── fontman/                             # Replacing .docx document fonts with simulated handwriting
    │       │   └── summarization_of_texts/              # TextRank implementation: lemmatization, sentence matrix similarity, ranking
    │       ├── video_generation/                        # Multimedia processing
    │       │   └── short_video_generation/              # moviepy + YAML config to generate Reels/Shorts from assets
    │       └── web/                                     # System web utilities
    │           ├── dns_proxy_blacklist/                 # DNS proxy server with upstream and domain blacklists
    │           └── net_port_scanner/                    # Asynchronous TCP port scanner supporting interface binding
    │
    ├── solana-webwallet/                                # ⭐ Solana Non-Custodial Telegram Wallet Bot
    └── tasks/                                           # 🗂️ Production, Commercial, and Applied Software (Python)
        ├── auto_ria_tracker/                            # Toyota Vehicle listing monitor bot with user alert interfaces
        ├── date_assistant/                              # Instagram Profile AI Analysis assistant
        ├── email_blast/                                 # Bulk personalized email sending script
        ├── email_sorter_pro/                            # Large scale email database sorting engine
        ├── fat32_disk_emulation/                        # Virtual 20 MB disk emulator mapping command-line commands
        ├── guess_the_card_game/                         # Standard card guessing game
        ├── human_body_mass_index/                       # Body Mass Index (BMI) calculator
        ├── numeric_data_file_analyzer/                  # Statistical analyzer for large numeric files
        ├── order-management-service/                    # K2 Order Bookkeeping module on Django Rest Framework
        ├── scraper/artikul_price_tracker/               # Wildberries e-commerce price monitor
        └── task_manager/                                # Django + HTMX task management board

---

## 📄 Core Project Descriptions

### 1. Dedicated Production Software (Primary Highlights)

#### `solana-webwallet`
- **Purpose:** A non-custodial wallet bot for the Solana blockchain running on Telegram via the `aiogram` framework.
- **Functionality:** Features dynamic generation of mnemonic keyphrases, secure importing of external accounts, local address checks, balance monitoring, SOL and token transactions, and a clean interface for checking ledger history.
- **Architecture:** The project divides logic into clean packages: `handlers` for command parsing, `keyboards` for inline control schemes, `external_services` executing RPC interactions with Solana endpoints, and a database storage adapter. Completely containerized for easy Docker deployment.

#### `tasks`
- **Purpose:** A curated folder of custom business automation utilities, client developments, and advanced tool designs.
- **Implementations:**
  - `auto_ria_tracker` — A real-time monitoring tool for automotive entries matching specific criteria on the AUTO.RIA portal. It uses a periodic HTML parser to track changes, compares records against a local SQLite database, and alerts users via `aiogram v3` channels.
  - `date_assistant` — An AI analysis program for public Instagram accounts. The application processes public bios and user metrics through OpenAI, Claude, and DeepSeek Large Language Models (LLM) to deliver tailored dating or networking feedback over streaming connections.
  - `email_blast` — A bulk email solution designed to dispatch custom newsletters to batches of up to ten thousand email recipients using data imported from CSV documents. Full delivery logs are recorded locally.
  - `email_sorter_pro` — A low-level file sorting application capable of indexing email data lists up to two hundred gigabytes. It categorizes domains geographically by matching them with top-level domain settings, directing unrecognized addresses to a fallback folder.
  - `fat32_disk_emulation` — A console application simulating a twenty-megabyte FAT32 virtual filesystem image. Supports commands such as `dir`, `cd`, `mkdir`, `create`, `cat`, and `rename`.
  - `guess_the_card_game` — A standard command-line prediction game simulating a virtual deck of cards, allowing users up to six guesses across multiple categories.
  - `human_body_mass_index` — A basic body mass index calculation utility, classifying entries inside standard World Health Organization health tiers.
  - `numeric_data_file_analyzer` — An analytical script scanning files containing long sequences of raw integers. It calculates minimum, maximum, median, and mean values while identifying the longest consecutive ascending and descending progressions.
  - `order-management-service` — The order administration component for the K2 Enterprise Resource Planning platform. It exposes REST endpoints for Client, Product, and Order database entities through custom serializer layers, features TypeScript UI configuration forms, is documented with Swagger/ReDoc schemas, and includes unit test coverage written in pytest.
  - `scraper/artikul_price_tracker` — An automated price tracking utility monitoring target items on Wildberries by processing dynamic identifiers through Selenium. The compiled price points are structured and saved as Excel reports using openpyxl.
  - `task_manager` — A task administration interface written in Django and utilizing HTMX for real-time changes without full webpage reloads. Equipped with both development and production configurations supporting Nginx proxies and PostgreSQL database environments.

---

### 2. Systems Programming & Networking in C (`educationalProjects / C`)

#### `Linux_kernel_modules`
- `hello-1..5` — Implementation of standard Loadable Kernel Modules (LKM) on Ubuntu, tracking module initialization, teardowns, parameters, and author metadata.
- `chardev/character_driver_for_tracking_reads` — A virtual character device tracking the frequency of system read calls.
- `chardev/ioctl` — A virtual device driver supporting custom Input-Output Control (ioctl) codes.
- `proc/proc-1..4` — Four distinct iterations demonstrating interfacing with the `/proc` filesystem, utilizing standard seq_file structures.
- `sysfs/hello-sysfs` — Exporting kernel module properties directly to the user space through sysfs attributes.
- `simple_hello` — Minimalist assembly analysis of basic programs using the gcc compiler and tracked through strace debugging.

#### `UNIX_Professionalnoe_programmirovanie_3-e_izd_2018`
- `directory_file_listing` — An alternative implementation of the standard POSIX directory list command (`ls`) utilizing custom `opendir()` and `readdir()` operations, yielding metadata outputs.

#### `network_programming`
- `getaddrinfo_example` — DNS hostname and port resolution utility supporting both IPv4 and IPv6 addresses via the standard `addrinfo` structure.
- `reverse_socks5_proxy` — A proxy architecture where the server inside the restricted network acts as a client to establish an outbound TCP connection, enabling secure administrative control.
- `unix_network_development_applications`:
  - `Time_and_Date_TCP_Client_and_Simple_Time_and_Date_Server` — Standard daytime TCP server alongside matching IPv4 and IPv6 clients.
  - `pieces_of_code_for_network_programming` — Structural templates showing byte conversions, host-to-network translations, and low-level IP parsing functions.
  - `UNIX_Network_Development_3rd_Edition/unpv13e` — Code patterns from W. Richard Stevens' Unix Network Programming textbook covering TCP/UDP sockets, I/O multiplexing (`select`, `poll`, `epoll`), and custom network diagnostic utilities.

#### `solutions_to_C_book_Exercises_Kernighan_Ritchie_3rd_Edition`
Seventeen challenges from Chapter 1 of the Kernighan & Ritchie C Programming Language book: covering basic I/O stream modifications, line folding, escape characters, space compression algorithms, histogram builders, temperature calculators, and string inversion exercises.

---

### 3. Object-Oriented C++ & Algorithms (`educationalProjects / C++`)

#### `TCPCommunication`
An implementation of client-server network interactions using standard BSD sockets. The TCP Server processes incoming connections, while the TCP Client dispatches custom string payloads.

#### `algorithms/sorting`
Contains sorting implementations: basic bubble sort variations (ascending, descending, and optimized with a modification flag), insertion sort with execution time measurements, and quicksort.

#### `arrays/working_with_dynamic_arrays`
Manual dynamic heap memory allocation utilizing custom array duplications, with elements randomly populated using hardware random number generators and mt19937 engines.

#### `class`
- `class_singly_linked_list` — A singly linked list class written without the C++ Standard Template Library.
- `class_string` — A custom string manager class built on standard `char*` arrays, implementing deep copies and custom memory cleanups.
- `decorator_coffee_consol` — An implementation of the Decorator design pattern for calculating custom combinations of coffee orders.
- `duck` — An implementation of the Strategy design pattern, demonstrating dynamic modifications to object behaviors at runtime.
- `map_and_multimap` — Core operations using `std::map` and `std::multimap` associative containers.
- `matrix` — A mathematical matrix container class with overloaded `[]`, `+`, `*`, and `<<` operators.
- `rectangle` — Demonstrates the Rule of Three with deep copy constructors, assignment operator overloads, and manual destructors.
- `stack_calculator` — A custom arithmetic expression evaluator built on a stack layout.
- `stack_data_structure` — LIFO stack mechanics (`push`, `pop`, `top`, `isEmpty`) implemented over custom memory blocks.
- `tasks/odd_numbers_to_beginning_even_numbers_to_end_array` — Shifts odd numbers to the beginning and even numbers to the end of a vector.

#### `dynamic_programming`
- `counting_trajectories_from_city_to_city` — Calculates the number of unique paths between nodes in Directed Acyclic Graphs.
- `digital_herringbone` — A pathfinding demonstration locating the maximum summation path in triangular numeric layouts.

#### `lafore_task`
Practice exercises from Robert Lafore's Object-Oriented Programming book:
- `3.1–3.4` — Fundamental class architectures and member methods.
- `chapter_4`: Basic operator overloads, usage of const methods, a card game simulation, and imperial measurement adapters.
- `chapter_7`: Abstract base classes, pure virtual interfaces, and polymorphic behaviors.

#### `struct`
- `queue` — A circular FIFO queue utilizing manual heap memory allocation.
- `students_name_and_grades` — A structured class validating student names, course lists, and grades.

#### `tasks/various_tasks`
- `algorithm_of_lexicographic_sorting` — Lexicographical sorting of custom string inputs.
- `parentheses/stack_parentheses` — A bracket parser checking brace balance using a stack.
- `simple_tasks` — Basic algorithm exercises including rounding, sorting, and mathematical summations.

---

### 4. Applied Python Frameworks (`educationalProjects / Python`)

#### `ai`
- `generating_images_from_text_OpenAI_and_ChatGPT` — Automated generation of graphics from text using the OpenAI DALL-E interface, including image saving and JSON logger outputs.
- `web_crawler_ads_generator` — Web scraper extracting details from pages using cloudscraper, summarizing them using OpenAI models, and exporting them as Google Ads CSV tables.

#### `api`
- `email_email_checking_and_verification_hunter` — A Python client verifying email addresses via Hunter.io API endpoints.
- `getting_access_token_to_artsynet_API_and_sorting` — An OAuth connection flow querying artist databases from Artsy.net, sorting entries by birth date.
- `hunter_check_mail` — An interactive email verification interface using SQLite databases to store check histories.
- `numbers_api_explorer` — An interactive terminal menu querying trivia, math, and date facts from numbersapi.com.

#### `audio_and_text`
- `add_words_and_music` — Converts text inputs into speech and mixes the resulting audio with background music.
- `convert_text_to_speech_in_python` — Voice synthesis using the lovoai API.
- `speech_to_text_library_speech_recognition` — Microphone recorder converting audio streams to text via SpeechRecognition libraries.
- `transcription_of_text_from_an_audio_file` — Audio transcriber demonstrating tiny, base, medium, and large Whisper configurations.

#### `BD/SQLite`
- `aggregation_and_grouping` — SQL tutorials covering database grouping, filtering, and aggregations.
- `commands_when_work_with_tables` — Standard database CRUD operations wrapped inside connection context managers.
- `first_steps_with_SQLite` — Connecting, configuring tables, populating rows, and running search queries.

#### `black_hat_python`
- `my_netcat` — A customized netcat utility supporting connections, port listening, multi-threading, and remote interactive shells.
- `scan` — Host discovery network scanner using ARP/ICMP requests.
- `tcp_client` — Custom TCP client scripts featuring detailed payload logs.
- `tcp_proxy` — A network proxy intercepting traffic and displaying formatting outputs via raw hex-dumps.
- `tcp_server` — A multi-threaded TCP server routing active connections into separate processing threads.

#### `bots / aiogram_2`
- `ai_checklist_guardian` — Location checklist generator utilizing `aiogram v2.25` and OpenAI.
- `telegram_bot` — Architectural template separating handlers, keyboards, and SQL database adapters.
- `telegram_bot_inline` — Interactive interfaces handling custom inline keyboards and callback data.

#### `bots / aiogram_3`
- `bot_guess_the_number` / `bot_guess_the_number_dictionary` — Guessing games using SQLite databases or in-memory dictionary storages.
- `bot_rock_paper_scissors` — Game logic and rules configured via Pydantic schemas.
- `callback_data_factory` — Structured callback operations using Callback Data Factories.
- `edit_messages` — Three distinct methods for editing and updating inline messages.
- `editing_messages_of_different_types` — Swapping active inline media types via `edit_message_media`.
- `form_filling_bot_fsm` — Questionnaire tracking user registrations with state diagrams.
- `formatting_text_in_messages` — Formatting text using HTML and Markdown inside Telegram messages.
- `improved_echo_bot` — Input-validating bot that handles text, stickers, audio, and documents.
- `middleware_example_bot` — Middlewares implementing logging, throttling, and role authorization checks.
- `naval_combat_game` — An 8x8 grid "Naval Combat" game using inline keyboards, state machines, and SQLite.
- `own_keyboard_generator` — Utility generating custom inline keyboard matrices.
- `telegram_bot_book` — A book reading bot featuring pagination and bookmarks stored in SQLite.

#### `class`
- `Is_the_class_an_ancestor` — Identifies class inheritance hierarchies using graph traversal.
- `MoneyBox_for_working_with_a_virtual_piggy_bank` — Piggy bank simulator tracking coin limits.
- `analogue_of_a_money_wallet` — Multi-currency wallet tracking balances and currency codes.
- `class_filter` — Multifilter implementing standard iterators to mimic built-in filter functions.
- `information_logging` — Mixin class appending logs to all method executions.

#### `crypto_world`
- `inter_exchange_arbitrage_bot` — Arbitrage finder using FastAPI, aiogram v3, and the CCXT library, with AI news analysis.
- `yobit_bot` — Automatic YoBit trader with Docker files, SQLAlchemy ORM mappings, and Alembic migrations.

#### `django`
- `backend` — Content Management System and blog platform incorporating authentication, Redis caching, Nginx proxying, and CKEditor.
- `money_convert_django` — Live currency converter tracking queries in conversion history models.
- `sitewomen` — Information portal built on custom Django template tags and advanced database queries.
- `zodiac_portal` — Horoscopes with dynamically routed URL requests.

#### `encrypt_and_decrypt`
- `creation_and_storage_of_logins_and_passwords` — Database-backed password manager using CRUD models in SQLite.
- `encrypt_and_decrypt_PDF_file` — PDF protection tool using password-based encryption.
- `encrypt_and_decrypt_all_files_in_directories_pyAesCrypt` — Recursive folder encryption using AES-256 algorithm.

#### `fast_api`
- `lang_chain_fast_summarizer` — Text summarization using FastAPI, LangChain, and Large Language Models.
- `quick_start_in_fastapi_python` — Eight microservices demonstrating cookies authentication, file servers, and registration schemes.

#### `spreadsheets`
- `excel_phonebook_parser` — Telegram bot parsing directory lists directly from Excel spreadsheets.
- `recover_payroll_from_payroll_records` — Reconstructs salary sheets from compressed ZIP files.
- `work_with_Pandas` — Data analysis covering groups, pivots, and filtration inside Pandas DataFrames.

#### `text`
- `fontman` — Modifies Microsoft Word (.docx) documents, replacing standard fonts with simulated handwriting.
- `summarization_of_texts` — Natural language processing utility sorting text importance via TextRank algorithms.

---

## ⚠️ Documentation Queue (README Files Pending Creation)

Below is a list of directory targets that do not currently contain dedicated README documentation files. Writing these is a planned task:

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
      python/django/book_shop/                     (Only "In Progress")
      python/django/cinema_guide/
      python/django/portfolio_master/
      python/django/sitewomen/
      python/fast_api/fast_api_post_manager/       (Empty)
      python/fast_api/lang_chain_fast_summarizer/
      python/flask/secure_hub/
      python/grpc/book_shop_grpc/                  (Empty)
      python/grpc/grpc_example/
      python/scraper/scrapy/
      python/black_hat_python/scan/
      python/video_generation/short_video_generation/
      python/text/fontman/
    
    tasks:
      tasks/date_assistant/                        (Empty)
      tasks/scraper/artikul_price_tracker/