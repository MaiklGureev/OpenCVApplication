# OpenCVApplication
Цель работы.

Целью данной лабораторной работы является разработка программы для распознания цветных круглых фигур на изображении с камеры в режиме реального времени, а также трассировка найденного объекта при движении.

Алгоритм.
1.	Перевод в RGB
2.	Поворот, флип и ресаиз изображения
3.	Размытие 
4.	Перевод фото в HSV формат
5.	Установка цветового диапазона
6.	Поиск цвета из заданного диапазона на HSV изображении
7.	Отрисовка контура / Поиск и отрисовка круга с цветным индикатором по центру для трассировки.

Описание приложения и скриншоты

Имеется возможность откорректировать цветовой диапазон для фигуры, передвинув по три верхних ползунка слева и справа. Параметры интервала задаются в формате HSV. Корректировка параметров поиска круглого объекта осуществляется передвижением трёх нижних ползунков. Два предустановленных цвета для поиска: зелёный и синий. Доступны два режима работы: поиск контуров и выделение круглого объекта на изображении заданного цвета.
