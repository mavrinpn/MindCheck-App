# MindCheck - мобильное приложение

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/main.png)

## Краткое описание

MindCheck - приложение для систем iOS и Android, написанное на фреймворке Flutter. Приложение позволяет пользователям регистрироваться и проходить психологические тесты и практики. Результаты чекапов, тестов и других активностей сохраняются в профиле пользователя. Для напоминаний о предстоящих тестах или необходимости пройти очередной чекап предусмотрены локальные уведомления.

## Реализованные фичи

Приложение сверстано согласно мокапам в Figma, всего в приложение порядка 25 различный экранов:

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/figma.png)

Приложение содержит несколько вкладок, каждая из которой имеет собственную ветвь навигации (пакет Go Router). В Bottom Navigation Bar находится вырез под Floating Button, которая раскрывается с плавной анимацией.

## Лента главного экрана

Лента представляет собой список карточек, которые меняются в зависимости от опытности и заинтересованности пользователя. В нее динамически выводится расписание пользователя, исходя из тех активностей, на которые он подписан.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/main_feed.png)

## Экраны списка Тестов, Техник и Практик

Данные экраны представляют собой список соответствующих активностей. В них есть фильтрация, различные по дизайну карточки, а также динамические баннеры с deeplink на соответствующие страницы приложения.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/tests.png)

## Экраны Аудио-, Видеоплеера и прохождения теста

Техники и Практики могут быть двух типов в зависимости от контента. При заходе в Технику/Практику автоматически открывается нужный плеер с полностью реализованным функционалом для упраления воспроизведеним. Если свернуть приложение на странице Аудиоплеера, то воспроизведение продожиться в фоновом режиме и в системный статусбар будет выведено соотвествующее уведомление.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/players.png)

## Экраны описания Курса и Теста

Данные экраны имееют расширенный AppBar (SliverAppBar), который адаптивно сворачивается при прокручивании страницы.
Графики пользовательского прогресаа выполнны с помощью пакета flutter_chart.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/overview.png)

## Результаты тестов и чекапов

Графики сделаны при помощи пакета flutter_chart, а также отрисованы в вкеторе на CustomPaint.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/results.png)

## Личный календарь пользователя

Кастомизированный календарь table_calandar позволяет хранить всю историю пользователя и добавлять новые события.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/calendar.png)

## Помощник дыхания

Анимированный виджет дыхания - анимация Lottie, скорость и длительность анимации управляется в коде - в зависимости от выбранной схемы дыхания.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/breath.png)

## Профиль пользователя и настройки

Профиль пользователся позволяет делать все необходимые действия - выбрать и отмасштабировать аватар, выполнить настройки уведомлений и получить нужную информацию.

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/profile.png)

## И многое другое...

В приложении также реализованы: нативный splash-screen, экраны welcome и loading, раличные формы записи к специалистам...

![MindCheck App](https://github.com/mavrinpn/MindCheck-App/raw/main/images/other.png)

## AppStore и GooglePlay

- Приложение скоро будет опубликовано в AppStore [App Store]()

- Приложение скоро будет опубликовано Google Play [Google Play]()

## Используемые пакеты и другие функции

- State Manager - Flutter BLoC
- Dependency Injections - GetIt
- Hive - медиатор для временного хранения некоторых данных
- Deeplinks для открытия разделов приложения из баннеров и советов
- Локализация - Easy Localization, поддержка двух языков
- Графики - fl_chart и отрисованные на CustomPaint
- Видео на полный экран - Chewie
- Фоновое аудио - Just_Audio
- Увндомления - flutter_local_notifications
- Кэш для изображений - cached_network_image

## Backend приложения

- В качестве серверной части используются сервисы Google Firebase: модули Auth, Firestore и Storage.
- Через Firestore реализована полная синхронизация учетной записи пользователя между разными устройствами.


My LinkedIn: [Pavel Mavrin](https://www.linkedin.com/in/pavel-mavrin-developer/)
