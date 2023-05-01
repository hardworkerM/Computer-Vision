# Computer-Vision
Выделение молекул пыли на картинке. Задача выделения контуров.

Команда: [Anton](https://github.com/oodlbee) |  [Grisha](https://github.com/hardworkerM)  |  Unknown


<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/0-5_1_5.png" alt="Пример картинки" width="300"/>

Выделение молекул пыли на картинке. Задача выделения контуров.

**Пайплайн решения:**
- Образеть картинку без нижней информации
- Для предобработки используем медианный фильтр для отсечения шума, эквализацию для лучшего выделения частиц от фона.
- Бинаризуем изобажение при помощи treshhold
- Выделяем контуры 
- Рисуем маску в соответствии с контурами

Описано в [main.ipynb](https://github.com/hardworkerM/Computer-Vision/blob/main/main.ipynb)

## Пайплайн в картинках

### Исходное изображение.
<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/пример.png" alt="Пример картинки" width="300"/>


### Предобработка изображения. 
<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/предобработка.png" alt="Пример картинки" width="300"/>

### Выделение маски
<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/маска.png" alt="Пример картинки" width="300"/>

### Наложение маски на начальное изображение маски
<img src="https://github.com/hardworkerM/Computer-Vision/blob/main/images/детекция.png" alt="Пример картинки" width="300"/>

