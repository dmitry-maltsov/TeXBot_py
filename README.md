# Latex_edit_bot
Курсовой проект по дисциплине технология программирования. </br>
Создание телеграмм бот с конвертированием ТеХ кода в картинку и теории по высшей математики.
# Команда разработки
1)Дмитрий Мальцов - Tech lead</br>
2)Рафаэль Темиргалеев</br>
3)Екатерина Фирсова</br>
4)Сергей Шарапов</br>
5)Григорий Степанов</br>
6)Сергей Салихов - Team lead</br>
# Требования к коммитам
"#issue_number", "#sprint_number", "active issue status", список добавлений.</br>
Пример: issue#2, sprint#1, Done, Добавлена реализация начального интерфейса.
# Примерный план на 5 спринтов
1 - ый спринт)Создание бота и его начального интерфейса.</br>
2 - ой спринт)Разработка конвертации тех кода в картинку.</br>
3 - й спринт) Создание интерфеса для высшай математики(опционально с подключением базы данных) и подключение конвертера.</br>
4 - й спринт) Доработка деталей проекта, общее тестирование, (опционально - добавление кнопок для тех конвертера), альфа тестирование.</br>
5 - й спринт) Бета тестирование и исправление багов, представляем финальную версию проекта, распространнение проетка.</br>
# StadpUp
Каждый участник отвечает на три вопроса:</br>
	1)Что я делал/делала в течении недели, чтобы помочь команде достичь цели спринта?</br>
	2)Чем я займусь на следующей неделе, чтобы помочь команде достичь цели спринта?</br>
	3)Вижу ли я препятствия, которые мешают мне или команде в достижении цели спринта?(и возможные корректировки процесса, для избежания этих препятствий)</br>
	
# Git workflow
https://habr.com/ru/post/106912/
# Принятый стиль кодирования
https://www.python.org/dev/peps/pep-0008/
</br>

# Deploy bot
Для размещения бота мы используем бесплатный сервер heroku(с иностранным ip адресом, чтобы избежать блокировки).</br>
Алгоритм размещения бота следующий:</br>
1)Подключаем GitHub репрезиторий к heroku(встроенная возможность).</br>
2)Создать "Procfile"(данные о приложении для сервера) && "requirments.txt"(что необходимо боту загрузить, для запуска приложения). Разместить их на GitHub репозитории.</br>
3)Запустить "deploy branch", и дождаться завершения.</br>
Выполнив эту последовательность действий бот будет размещён на сервере.
