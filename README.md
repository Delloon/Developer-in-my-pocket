## 📱Карманный разработчик

Карманный разработчик — это мобильное приложение, предназначенное для изучения программирования. Этот проект направлен на создание эффективного инструмента для обучения программированию с помощью хорошо структурированного и удобного мобильного приложения.

<br>
⚠️ Предоставленная информация о курсах предназначена исключительно для тестирования. Включены скриншоты и описания основного окна, окна с темами курса и окна урока приложения.

## 💻 Используемые технологии
![Firebase](https://img.shields.io/badge/-Firebase-090909?style=for-the-badge&logo=firebase&logoColor=F8C52C)
![Android Studio](https://img.shields.io/badge/-Android_Studio-090909?style=for-the-badge&logo=Android&logoColor=FFFF)
![Kotlin](https://img.shields.io/badge/-Kotlin-090909?style=for-the-badge&logo=Kotlin)

## 🌟 Актуальность
С развитием IT-технологий и ростом спроса на специалистов, всё чаще люди обращаются к различным обучающим сервисам. Одним из таких решений являются мобильные приложения, которые становятся все более актуальным средством для получения информации.

## 🎯 Цели и задачи
Цель проекта — разработка мобильного приложения для изучения программирования. Для достижения этой цели были выполнены следующие задачи:

<ul>
   <li>Анализ и описание предметной области</li>
   <li>Проектирование приложения, включая обзор и выбор инструментальных средств разработки</li>
   <li>Разработка технического задания</li>
   <li>Построение UML-диаграмм</li>
   <li>Реализация логической и физической модели базы данных</li>
</ul>


## 📚 Диаграмма классов
На диаграмме классов представлены основные классы приложения и их взаимодействия. Ключевые классы включают:

<ul>
   <li>Course, Lesson, Theme, User и UserCourseProgress, которые определяют структуру данных.</li>
   <li>MainActivity, AuthActivity, CourseActivity и ThemeActivity управляют навигацией и взаимодействием с пользователем.</li>
   <li>ProfileFragment и CourseFragment отображают окна профиля пользователя и список курсов.</li>
   <li>DatabaseManager управляет данными.</li>
   <li>Адаптеры (CourseAdapter, ThemeAdapter, LessonAdapter) связывают данные с интерфейсом приложения.</li>
</ul>


   ![Диаграмма классов](https://github.com/Delloon/Developer-in-my-pocket/blob/main/images/classDiagramm.png)

## 📊 Логическая модель

Логическая модель NoSQL отражает все таблицы из реляционной логической модели, за исключением того, что таблицы CompletedLesson и LessonPart являются подколлекциями основных коллекций Lessons и CourseData.<br>
   ![Логическая модель](https://github.com/Delloon/Developer-in-my-pocket/blob/main/images/logicalModel.png)

## 📲 Использование

1. Запустите приложение на устройстве.
2. Войдите в систему или зарегистрируйтесь.
3. Просматривайте доступные курсы и выбирайте нужный для изучения.
4. Следуйте урокам курса, отвечайте на контрольные вопросы и отслеживайте свой прогресс.



## 🖼️ Скриншоты

1. **Главное окно**: отображает список курсов, последний изучаемый курс и список полезных советов, обновляющихся каждый час из базы данных.<br>

2. **Окно с темами курса**: показывает список тем с вложенным списком уроков. Темы можно скрывать и раскрывать. Для отображения данных используется RecyclerView, обеспечивающий динамическое отображение данных.<br>

3. **Окно урока**: открывается при нажатии на урок. Содержит название урока, текст урока и кнопку для завершения урока. В тексте урока могут быть теги для изображений, такие как `[img:image_name]`, которые заменяются на соответствующие изображения из ресурсов приложения с помощью метода `addTextContent`.<br>

<div style="text-align: center;">
<img src="https://github.com/Delloon/Developer-in-my-pocket/blob/main/images/1.jpg" alt="Главное окно" width="20%">
<img src="https://github.com/Delloon/Developer-in-my-pocket/blob/main/images/2.jpg" alt="Окно с темами курса" width="20%">
<img src="https://github.com/Delloon/Developer-in-my-pocket/blob/main/images/3.jpg" alt="Окно урока" width="20%">
</div>

## 📜 Лицензия

Этот проект лицензирован на условиях закрытой лицензии. Все права на проект принадлежат автору. Перераспределение и использование в коммерческих приложениях строго запрещены без предварительного письменного разрешения. Подробнее см. в [LICENSE](LICENSE)
