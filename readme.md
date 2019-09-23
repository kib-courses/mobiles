# Спецкурс "Безопасность мобильных приложений (Android)"
**Дата проведения**: октябрь-ноябрь 2019

## Поступление на спецкурс

На спецкурс "автоматом" поступили все, кто успешно завершил прошлый спецкурс: 
"разработка приложений под Android". В осеннем семестре 2019 года -- это пять человек.

Остальным для поступления на спецкурс необходимо:
1. Выполнить вступительное задание до **6 октября 23:59**. Сдача по почте.
2. Заполнить форму
https://docs.google.com/forms/d/e/1FAIpQLSdx3jGogG_rV6nxkPP-AKtFlK5ns3XmDsZ7wE0zh4q6A2ePgw/viewform


Вступительное задание:

  * Создать android-приложение работающие с **minApi=19** и при запуске осуществляющее резервное копирование контактов и sms пользователя в текстовый файл.

Важно:
  * Файл должен располагаться в **external storage**, в **ui** выводить путь к файлу.
  * Самостоятельный поиск необходимой информации -- часть задания.
  * Сдача через почту. Делайте **заранее**, чтобы было время переделать.

## Планируемые темы курса

**Тема 1. Введение в безопасность мобильных устройств. Основы мобильного ПО**

  1. Введение в курс.
  1. Общий план занятий 
  1. Сравнение аспектов безопасности систем iOS и Android 
  1. Обзор вредоносных программ для мобильных платформ 
  1. Введение в ОС Android (Архитектура, Android SDK, API Level, adb, aapt, apktool)
  1. APK и процесс компиляции
  1. Жизненные циклы приложения Android. Мобильная разработка Android
  1. Жизненные циклы приложения iOS. Мобильная разработка iOS
  1. Документация (Android Security Review/Security for Android Developers, Apple Secure Coding Guide)
  1. Пример исходного кода приложения

**Тема 2. Хранение данных. Утечки данных. Межпроцессное взаимодействие**
  
  1. Файловая система. 
  1. Внутренняя архитектура ФС Android. 
  1. SELinux 
  1. Внутреннее хранилище приложений 
  1. SQLite 
  1. Небезопасное хранение данных
  1. Хранение данных и права доступа в iOS. Пример приложения iOS
  1. Jailbreak & root
  1. Keychain, KeyStore
  1. Биометрические системы
  1. Логи процесса работы приложения
  1. Межпроцессное взаимодействие

**Тема 3. Основы аудита мобильных приложений.**
  
  1. OWASP
  1. Аудит мобильных приложений. Модели аудита (white/black/grey box)
  1. Keyloggers, фишинг 
  1. Обзор OWASP Top10 Mobile
  1. Шифрование данных (Ключи, подпись приложений. Шифрование в iOS)
  1. Непредусмотренная функциональность. Backdoors 
  1. Небезопасная аутентификация и авторизация (Hashes, авторизация JWT)

**Тема 4. Реверс-инжениринг. Статический и динамический анализ кода**

  1. Реверс-инжениринг. Статический и динамический анализ
  1. Декомпиляция 
  1. Введение в smali FindBugs / FindSecBugs / QARK Tampering. 
  1. Пример изменения логики работы приложения.
  1. Введение в динамический анализ (iOS Sandbox)
  1. AndBug, Frida, XPosed
  1. Инъекция в исходный код

**Тема 5. Декомпиляция, деобфускация. Передача данных по сети**

  1. Обфускация и деобфускация
  1. NDK
  1. Валидация пользовательского ввода
  1. Неправильное использование ресурсов платформы
  1. Передача чувствительных данных
  1. Небезопасная передача данных по сети – Pinning Certificate
