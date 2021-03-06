## Шаблон Композиция (Composite) ##

### Цел на шаблона ###

Шаблонът "Композиция" се прилага при работа с йерархични структури от обекти, като ни дава възможност да работим с цели клонове от йерархията по същия начин, като с отлените елементи в нея. Резултатът е опростен код и изчистена логика.  

![](https://github.com/vesheff/Telerik/blob/master/08.High%20Quality%20Code/16.StructuralPatterns/img/composite.png)

### Приложимост ###

- Имплементиране на обекти като дървета, за да се представят йерархии от обекти.

- Позволява клиентът да работи както с отделните обекти, така и с композитните по един и същ начин. 

### Участници ###

- Component - Абстракция на всички компоненти, вклчително и композитните. Дефинира интерфейс за всички обекти в композицията.

- Leaf - Представлява имплементацията на всички Component методи.

- Composite - Представлява композитен компонент, който има деца. Съдържа методи, чрез които манипулира децата си. Имплементира всички методи, чрез децата си.  


### Приложения ###
DOM дървото в JS. 

### Свързани шаблони ###
„Интерпретатор“ (Interpreter)


### Имплементация ###
[Examples](https://github.com/vesheff/Telerik/tree/master/08.High%20Quality%20Code/DesignPatterns-Examples)

```c#
    
```
