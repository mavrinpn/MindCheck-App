![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/main.png)

# Краткое описание

MindCheck - приложение для систем iOS и Android, написанное на фреймворке Flutter. Приложение позволяет пользователям регистрироваться и проходить психологические тесты и практики. Результаты чекапов, тестов и других активностей сохраняются в профиле пользователя. Для напоминаний о предстоящих тестах или необходимости пройти очередной чекап предусмотрены локальные уведомления.

# Реализованные фичи

Приложение сверстано согласно мокапам в Figma, всего в приложение порядка 25 различный экранов:

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/figma.png)

Приложение содержит несколько вкладок, каждая из которой имеет собственную ветвь навигации (пакет Go Router). В Bottom Navigation Bar находится вырез под Floating Button, которая раскрывается с плавной анимацией.

# Лента главного экрана

Лента представляет собой список карточек, которые меняются в зависимости от опытности и заинтересованности пользователя. В нее динамически выводится расписание пользователя, исходя из тех активностей, на которые он подписан.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/main_feed.png)

# Экраны списка Тестов, Техник и Практик

Данные экраны представляют собой список соответствующих активностей. В них есть фильтрация, различные по дизайну карточки, а также динамические баннеры с deeplink на соответствующие страницы приложения.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/tests.png)

# Экраны Аудио- и Видеоплера

Техники и Практики могут быть двух типов в зависимости от контента. При захоже в Технику/Практику автоматически открывается нужны плеер с полностью реализованным функционалом для упраления воспроизведеним. Если свернуть приложение на странице Аудиоплеера, то воспроизведение продожиться в фоновом режиме и в системный статусбар будет выведено соотвествующее уведомление.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/players.png)

# Экраны описания Курса и Теста

Данные экраны имееют расширенный AppBar (SliverAppBar), который адаптивно сворачивается при прокручивании страницы.
Графики пользовательского прогресаа выполнны с помощью пакета flutter_chart.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/overview.png)


# Результаты тестов и чекапов

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/results.png)

# Личный календарь пользователя

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/calendar.png)


# Помощник дыхания

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/breath.png)

# Профиль пользователя и настройки

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/profile.png)


# И многое другое

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/other.png)


## AppStore и GooglePlay

- Приложение скоро будет опубликовано в AppStore [App Store]()

![AppStore Link](https://github.com/mavrinpn/Svetofon-App/raw/main/img/AppStore.png)

- Приложение скоро будет опубликовано Google Play [Google Play]()

## Другие функции

- Локальная база данных Hive


## Backend

- в качестве серверной части используются сервисы Google Firebase: Auth, Firestore и FireStorage.
- через Firestore реализована полная синхронизация учетной записи пользователя между разными устройствами.



My LinkedIn: [Pavel Mavrin](https://www.linkedin.com/in/pavel-mavrin-developer/)
