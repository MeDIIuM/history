history
=======

**Historical school project**

*Установка:*

	Установить git, усли его нет:
		sudo apt-get install git
	Из коммандной строки войти в нужную папку и ввести комманду
		git clone https://github.com/MeDIIuM/history.git  (ссылка справа)
	Открыть в браузере index.html
	В phpstorm открыть VCS/Enable version control integration.
	Выбрать из списка Git и нажать ок.
	Файлы в phpstorm будут помечаться:
		красным(не добавленые в гит),
		зеленым(новые, добавленые),
		синим(измененые)

*Сохранение изменений:*

	VCS/commit changes. Поставить галочку Reformat code(для форматирования).
	Ввести описание изменений.
	Нажать кнопку commit.

*Для отправки изменений на github:*

	VCS/Git/Push. Далее выбрать ветку( по умолчанию - master) и нажать ok.