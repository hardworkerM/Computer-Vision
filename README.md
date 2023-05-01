# Computer-Vision
Computer Vision task -  detecting dust molecules in images

Задача на обнаружение молекул пыли 

<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/0-5_1_5.png" alt="Пример картинки" width="300"/>


## Задача на классический OpenCV. 
__не на нейронные сети__<br>
Все сводится к выделению контуров и наложением маски

<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/пример.png" alt="Пример картинки" width="300"/>


### Предобработка изображения. 
Медианный фильтр для отсечения шума, Эквализация для лучшего выделения частиц от фона.<br>
**Результат:**

<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/предобработка.png" alt="Пример картинки" width="300"/>

В целом дальше производим манипуляции описаные в [main.ipynb](https://github.com/hardworkerM/Computer-Vision/blob/main/main.ipynb)

В результате получаем прекрасное выделение 

<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/маска.png" alt="Пример картинки" width="300"/>
<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/детекция.png" alt="Пример картинки" width="300"/>

