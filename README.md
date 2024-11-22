# PyGravity
  Симуляция гравитационного взаимодействия между телами

### Описание программы
	Данная программа позволяет проследить движение и взаимодействие объектов 
	различной массы и формы под действием сил гравицтации.
	У каждого объекта в программе есть свои параметры:
		X - положение объекта по оси x,
		Y - положение объекта по оси y,
		R - радиус объекта,
		Velocity - скорость,
		K -коэффициент упругости,
		M - масса,
	по которым высчитываются силы и перемещение всех тел.

### Инструкция по запуску 
	Чтобы запустить программу надо собрать все файлы в одной папке и запустить файл main.
	Для запуска необходмы установленные библиотеки Tkinter, numpy

### Описание интерфейса
	Кнопка «Start» - начать симуляцию
	Кнопка «Stop» - остановить симуляцию
	Кнопка «Reset» - сбросить скорость
	Кнопка «Добавить» - добавление объекта на поле симуляции*
	Кнопка «Удалить» - удаление объекта с поля симуляции
	Кнопка «Изменить» - изменение свойств объекта**

	*объект без имени не может быть добавлен
	**ячейки должны быть обязательно заполнены числами(допустим тип float)
