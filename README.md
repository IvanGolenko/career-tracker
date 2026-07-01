# Career Tracker

<p align="center">
  <img width="619" height="320" alt="Career Tracker screenshot" src="https://github.com/user-attachments/assets/7935a2a1-a7ea-48c1-a562-93f10bddcdf4" />
</p>

<p align="center">
  <a href="https://github.com/IvanGolenko/career-tracker/releases/latest">
    <img src="https://img.shields.io/badge/Скачать_актуальную_версию-Career_Tracker-blue?style=for-the-badge" alt="Скачать Career Tracker" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-desktop_app-black?style=flat-square" />
  <img src="https://img.shields.io/badge/Python-Django-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/данные-локально-green?style=flat-square" />
  <img src="https://img.shields.io/badge/версия-1.3.0-orange?style=flat-square" />
</p>

**Career Tracker** — настольное приложение для macOS, которое помогает спокойно вести учёт откликов на вакансии.

Приложение сделано для личного использования: **один Mac, один владелец, одна локальная база данных.**

---

## 🧭 Зачем приложение необходимо

<p align="center">
  <img width="1279" height="688" alt="Снимок экрана 2026-06-30 в 12 41 58" src="https://github.com/user-attachments/assets/d546508a-dece-42d2-8e63-78a1f40cd221" />
</p>

Когда откликов становится много, обычных заметок и закладок уже не хватает. Вакансии теряются, статусы забываются, а поиск работы начинает ощущаться беспорядочным.

Career Tracker помогает спокойно разложить процесс по полочкам: хранить отклики, отслеживать этапы, быстро находить нужные вакансии и понимать, что происходит с поиском прямо сейчас.

---

## ✨ Что умеет

- создавать карточки откликов;
- хранить компанию, вакансию, ссылку, зарплату, контакты и заметки;
- автоматически заполнять данные вакансии по ссылке;
- отмечать статус отклика;
- искать по откликам;
- фильтровать отклики по статусам;
- отправлять карточки в корзину и восстанавливать их;
- экспортировать данные в Excel;
- защищать приложение PIN-кодом;
- хранить данные локально на устройстве.

---

## 🔐 Приватность

Career Tracker не использует облако и не отправляет данные на сервер.

Все данные хранятся локально на вашем Mac.

---

## 🛠️ Технологии

Проект собран как desktop-приложение поверх Django:

- Python
- Django
- SQLite
- HTML / CSS
- Bootstrap
- openpyxl
- pywebview
- PyInstaller

---

## 📦 Скачать

Актуальная версия приложения доступна в разделе:

[**Releases**](https://github.com/IvanGolenko/career-tracker/releases/latest)

Файл для macOS выглядит примерно так: `CareerTracker-1.3.0-macOS.zip`

---

## 🍏 Первый запуск на macOS

<p align="center">
<img width="823" height="208" alt="Снимок экрана 2026-06-26 в 19 22 46" src="https://github.com/user-attachments/assets/1033a74e-04eb-4b29-88e2-486c3996cedb" />
</p>

При первом запуске macOS может показать предупреждение:

> Apple не удалось подтвердить, что файл «Career Tracker» не содержит вредоносного ПО.

Это стандартное предупреждение для приложений, которые распространяются напрямую через GitHub Releases и не подписаны через Apple Developer ID.

Чтобы открыть приложение:

1. Распакуйте `CareerTracker-1.3.0-macOS.zip`.
2. Найдите `Career Tracker.app`.
3. Нажмите по приложению правой кнопкой мыши.
4. Выберите **Открыть**.
5. В появившемся окне снова нажмите **Открыть**.

Если кнопки открытия нет:

1. Откройте **System Settings**.
2. Перейдите в **Privacy & Security**.
3. Пролистайте вниз до сообщения о заблокированном приложении.
4. Нажмите **Open Anyway** / **Всё равно открыть**.
5. Подтвердите запуск.

После первого подтверждения приложение будет открываться обычным двойным кликом.

---

## 👤 Для кого это приложение

Career Tracker подойдёт тем, кто активно ищет работу и хочет вести отклики спокойно, без таблиц, заметок и хаоса в закладках.

Особенно полезно, если вы откликаетесь на десятки вакансий и хотите видеть весь процесс в одном месте.

---

**Автор: Ivan Golenko**
