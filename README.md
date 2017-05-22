# Лабораторная работа 1 (выполнение до 21 февраля).

##Цветовые модели.
##Задача
![Смотри картинку...](https://github.com/CG2017/_Workflow/blob/master/3-15.jpg) 
Создать приложение/веб-приложение, позволяющее пользователю  выбирать, а затем интерактивно менять цвет, показывая при этом его составляющие в нескольких моделях одновременно (модели для вашего варианта приведены на странице 2).
На проверку сдаются:      
• exe, который должен работать на ПК преподавателя под Windows /веб-приложение, размещенное в общем доступе;     
• исходный код приложения на gitHub;    
• сопроводительная документация (например, если пользовались внешней библиотекой, то инструкция где ее скачать).

*Основные требования к приложению*
В интерфейсе дать возможность пользователю задавать точные цвета (поля ввода хотя бы для RGB), выбирать цвета из палитры (аналогично графическим редакторам), плавно изменять цвета (например, ползунки).
При изменении любой компоненты цвета все остальные представления этого цвета во всех цветовых моделях пересчитываются автоматически
При "некорректных цветах" (например, при переходе из XYZ в RGB в вашем расчете получился выход за границы изменения рассчитываемого параметра) выдавать некое ненавязчивое предупреждение, что происходит обрезание-округление и т.п.

*Как получить дополнительные баллы*     
•	Около ползунков с изменением компоненты цвета добавить градиентный background, чтобы можно было видеть заранее, к чему приведёт изменение его положения.     
•	Использовать несколько вариантов расчета компоненты K в модели CMYK. Дать возможность грамотного обратного преобразования в RGB, если пользователь меняет только K.     
•	Приложение, написанное на native JavaScript, добавляет баллы в рейтинг Барвенову      
•	Разобраться и запрограммировать работу с  моделями YUV • YDbDr • YIQ  • YPbPr  • YCbCr.      
_Имеется в виду не просто взять ГОТОВЫЕ формулы в матричном виде с десятичными константами (из wiki или сети), а разобраться и понять, почему в разных источниках приводятся разные формулы для расчета. Разобравшись, дать возможность менять константы, используемые для расчета коэффициентов преобразования (например, точки белого или параметров источника освещения). Предпочтительно использовать целочисленную арифметику в матрицах._

##Цветовые модели по вариантам:
*Внимание! В таблице написано RGB, а не sRGB. Внимательно копируйте формулы из wiki. Также в таблице написано CMY, а не CMYK.*

1	RGB	CMY	HSV	L*u*v     
2	RGB	CMY	HSV	Lu'v'     
3	RGB	CMY	HSV	L*a*b     
4	RGB	CMY	HSV	L*u*v     
5	RGB	CMY	HSV	Lu'v'     
6	RGB	CMY	HLS	L*a*b     
7	RGB	CMY	HLS	L*u*v     
8	RGB	CMY	HLS	Lu'v'     
9	RGB	CMY	HLS	L*a*b     
10	RGB	CMY	HLS	L*u*v     
11	RGB	CMY	HSV	Lu'v'      
12	RGB	CMY	HSV	L*a*b     
13	RGB	CMY	HSV	L*u*v     
14	RGB	CMY	HSV	Lu'v'      
15	RGB	CMY	HSV	L*a*b     
16	RGB	CMY	HLS	L*u*v     
17	RGB	CMY	HLS	Lu'v'     
18	RGB	CMY	HLS	L*a*b     
19	RGB	CMY	HLS	L*u*v     
20	RGB	CMY	HLS	Lu'v'     
21	RGB	CMY	HSV	L*a*b      
22	RGB	CMY	HSV	L*u*v     
23	RGB	CMY	HSV	Lu'v'     
24	RGB	CMY	HSV	L*a*b     
25	RGB	CMY	HSV	L*u*v      

# Тут оценки и коментарии

|Прозвішча                      |  Lab1                       |Lab2 |Lab3 |Lab4 |Lab5 | Lab6|Lab7 |Lab8 |Lab9|Коллоквиум| Итого
|:------------------------------|:---------------------------:|----:|:---:|----:|:---:|----:|----:|----:|-----:|-----:|-----:|
|Рыжевич                        | 128(JS +XY)                 | 100 | 256 |  100| 100(совместно с Шило) | 100 |  
|Жидков                         | 140(JS +background sliders) | 100 | 100 |  100| 100  |     |     |  
|Вычев                          | 100                         |  99 | 100 |  99(костыли)|99 | 100 |     |  
|Савчук                         | 100                         | 100+20(веса)|100+20| 100 |100 | 100 |  
|Ильяшевич Катя                 | 100                         | 100 | 100  | 100 | 90(код Шило) | 100 |  
|Шило Денис                     | 120(+background sliders)    | 100 | 100  | 100 | 100(поделился с Катей)|     | 100 |  
|Яковцева                       | 100                         | 100+20(веса) | 100  | 100 | 100  | 100 |     |
|Пакальнишкис                   |100                          | 90  |99(UI)| 50(pcx)|
|-----------------|
|Ромаш                          |100 | 100| 100|100+10|100|
|Султонов                       |120 |100| 100+20|90|
|Венский                        | 95 | 120(Js)| 100 |100|100| 
|Торопов                        |120(+background sliders)| 100| 100| 90|99(gap)|
|Кононович                      |100| 99 |100 |99(Проверить gif с ppi=183)| 
|Гурская                        |100| 50(синий) |100|90(tiff3)|
|Атрощенко      +-              |100|90|
|Пасечник  Никитос  (git)       | 95 |???(evklid) | 90 | 90(pcx)|100|
