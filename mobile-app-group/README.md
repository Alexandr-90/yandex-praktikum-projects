#  Выделение групп пользователей на основе поведения

Проект можно посмотреть [здесь](https://nbviewer.jupyter.org/github/Alexandr-90/yandex-praktikum-projects/blob/master/mobile-app-group/mobile-app-group.ipynb).

## Цель

Выделить группы пользователей на основе данных об их действий при использовании приложения.  

## Задачи
 
Выделить группы пользователей, которые различаются по метрикам:
- retention rate,
- время, проведённое в приложении, 
- частота действий, 
- конверсия в целевое действие — просмотр контактов.  
Проверить статистические гипотезы:  
1. *Некоторые пользователи установили приложение по ссылке из `yandex`, другие — из `google`. Проверьте гипотезу: две эти группы демонстрируют разную конверсию в просмотры контактов.*
2. *Пользователи, которые обращаются к функции поиска по объявлениям демонстрируют лучшую конверсию в просмотры контактов.*

## Используемые библиотеки

*pandas  
matplotlib  
numpy  
seaborn  
plotly  
scipy  
math  
sklearn*

## Итог

Для сегментации пользователей была сформирована таблица признаков для каждого пользователя.  
Используя Machine Learning было определено оптимальное количество групп, на которые были разбиты пользователи, путём кластеризации.  
Были изучены ключевые метрики в разрезе групп.  
Проверены гипотезы.  
Сделаны выводы и предложены рекомендации дальнейших действий.  
По результатам была подготовлена презентация и Dashbord.  

[Notebook](https://nbviewer.jupyter.org/github/Alexandr-90/yandex-praktikum-projects/blob/master/master/mobile-app-group/master/mobile-app-group.ipynb)
