[HW_2 : Terminal. Format : JSON](https://github.com/Vitaly-chek/JSON)

[HW_2 : Terminal. Format : TXT](https://github.com/Vitaly-chek/TXT)

[HW_1 : Terminal](https://github.com/Vitaly-chek/Terminal)

[HW_1 : Git](https://github.com/Vitaly-chek/Git)

---

# HW_2 : XML

1. Создать внешний репозиторий c названием XML;

2. Клонировать репозиторий XML на локальный компьютер - `git clone URL`;

3. Внутри локального XML создать файл “new.xml” - `git touch new.xml`;

4. Добавить файл под гит - `git add .`;

5. Закоммитить файл - `git commit -m "create new file"`;

6. Отправить файл на внешний GitHub репозиторий - `git push`;

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML:

```
<?xml version="1.0" encoding="UTF-8"?>
<info>
	<about_me>
		<name> Vitaly </name>
		<lastname> Krivoruchek </lastname>
		<age> 23 </age>
		<pets> 3 </pets>
	</about_me>
	<work>
		<position> QA Engineer </position>
		<salary> 600 </salary>
		<currency> USD </salary>
	</work>
</info>
```

8. Отправить изменения на внешний репозиторий - `git commit -am "updated file" / git push`;

9. Создать файл preferences.xml - `touch preferences.xml`;

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML:

```
<?xml version="1.0" encoding="UTF-8"?>
<preference>
	<favorite_movie> Волк с Уолл-стрит </favorite_movie>
	<favorite_series> Сотня </favorite_series>
	<favorite_food>
		<1> Окрошка </1>
		<2> Жареная картошка </2>
	</favorite_food>
	<favorite_season> 
		<1> Лето </1>
		<2>	Осень </2>
	</favorite_season> 
	<favorite_countries>
		<1> Швейцария <1/>
		<2> Канада </2>
	<favorite_countries>
</preference>
```

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML - `touch skills.xml`:

```
<?xml version="1.0" encoding="UTF-8"?>
<skills>
	<1> Базовая теория </1>
	<2> Что такое клиент-серверная архитектура </2>
	<3> HTTP Методы запросов на сервер </3>
	<4> Коды ответов HTTP сервера </4>
	<5> Структуры HTTP запросов и ответов </5>
	<6> Что такое JSON, XML. Их структура </6>
	<7> Тестировнаие API через Postman (JS, автотесты API) </7>
	<8> Снятие и чтение логов с внешнего сервера </8>
	<9> Снифинг http web трафика через Charles и Fiddler </9>
 	<10> Dev Tools веб браузеров (Google Chrome, FireFox) </10>
	<11> VPN. (Как работает, зачем нужен, как использовать, варианты инструментов) </11>
	<12> Мобильное тестирование </12>
	<13> Особенность iOS, Android, гайдлайны </13>
	<14> Сборка iOS приложений на XCode </14>
	<15> Сборка Android приложений на Android Studio </15>
	<16> ADB (управление андройд девайсами) </16>
	<17> Настройка прокси и vpn на iOS и Android </17>
	<18> Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android </18>
	<19> Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса) </19>
	<20> Основы bash скриптинг, автоматизация рутинных задач на сервере </20>
	<21> Доступ к удалённым серверам </21>
	<22> Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join) </22>
	<23> База данных Postgres (установка, настройка и использование) </23>
	<24> Нереляционная база данных Redis (установка, настройка и использование) </24>
	<25> Нагрузочное тестирование в Jmeter </25>
	<26> Методология разработки Scrum </26>
</skills>
```

12. Сделать коммит в одну строку - `git add . && git commit -m "2 new files"`;

13. Отправить сразу 2 файла на внешний репозиторий - git push;

14. На веб интерфейсе создать файл bug_report.xml;

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе:

```
<?xml version="1.0" encoding="UTF-8"?>
<bug_report>
  <project> Заметки </project>
  <version> 1.3 </version>
  <id> №5 </id>
  <summary> При клике на кнопку фильтрации 'A to Z' на главной странице приложения происходит хаотичная фильтрация списков </summary>
  <step_to_reproduce>
    <1> Открыть приложение 'Заметки' </1>
    <2> Создать 15 списков, которые будут начинаться соответственно (A, a, D, 3, :, U, u, Ш, ш, 5, @, Ї, ї, -, d) </2>
    <3> На главной странице приложения ликнуть на кнопку фильтрации 'A to Z' </3>
  </step_to_reproduce>
  <actual_result> Списки сортируются хаотично </actual_result>
  <expected_result>  
    <1> Списки сортируются по порядку: символы, цифры, буквы латиницы (сначала верхний регистр), буквы кириллицы (сначала верхний регистр) </1>
    <2> Правильный порядок : (-, :, @, 3, 5, А, а, D, d, U, u, Ї, ї, Ш, ш) </2>
  </expected_result>
  <severity> Minor </severity>
  <priority> Normal </priority>
  <status> New </status>
  <environment> IPhone 7 Plus, version 15.4.1 </environment>
  <author> Vitaly </author>
  <assignee> Ivan </assignee>
</bug_report>
```

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML;

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе;

18. Синхронизировать внешний и локальный репозиторий XML - `git pull`.
