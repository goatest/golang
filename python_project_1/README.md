## README.md for GitHub

---

# **Защита "Системной Информации" в ОС**

Проект по созданию защищенного файлового хранилища для хранения системной информации на локальном компьютере.

---

## 📌 Оглавление

- [Основной функционал](#основной-функционал)
- [Инструкции по использованию](#инструкции-по-использованию)
- [Контакты разработчика](#контакты-разработчика)

---

## 🛠 Основной функционал

1. **sys.tat**  
    - Текстовый документ содержащий информацию о системе.

2. **sys_doc.exe (Инсталлятор)**  
    - Запрашивает папку для сохранения.
    - Копирует `secur.exe`.
    - Собирает, шифрует и записывает информацию.
    - Создает и сохраняет подпись.
    - Запускает `secur.exe` для защиты.
    - Привязывает `secur.exe` к `sys.tat`.

3. **secur.exe (Программа защиты)**  
    - Проверяет подпись пользователя.
    - Регулирует доступ к "Системной информации".

4. **Обработка ошибок**  
    - При ошибке прекращает доступ к программе.

5. **Системная информация**  
    - Имя пользователя, компьютера.
    - Конфигурация компьютера.
    - Версия ОС.

---

## 📖 Инструкции по использованию

1. **Установка**  
Запустите `sys_doc.exe` и следуйте инструкциям.

2. **Использование**  
При попытке открыть `sys.tat`, запустится `secur.exe`. Введите имя раздела реестра для верификации.

3. **Доступ к информации**  
После верификации просмотрите информацию в `sys.tat`.

---



---

💡 Проект создан в рамках академического задания и может содержать ошибки или недоработки.
