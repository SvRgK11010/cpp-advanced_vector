# Advanced vector
Финальная версия учебного проекта курса "Разработчик C++" Яндекс.Практикум

### Описание 
Реализация контейнера, аналогичного по эффективности std::vector.

### Функционал
В проекте реализованы следующие функции:
* Resize - изменяет количество элементов в векторе;
* Reserve - изменяет объём зарезервированной памяти;
* PushBack - добавляет новое значение в конец вектора;
* PopBack - разрушает последний элемент вектора и уменьшает размер вектора на единицу;
* EmplaceBack - предоставляет возможность создать элемент вектора в его конце, возвращает ссылку на добавленный элемент;
* Insert - вставляет элемент в заданную позицию вектора;
* Emplace - позволяет конструировать элемент вектора в заданной позиции, используется perfect forwarding;
* Erase - удаляет элемент, на который указывает переданный итератор.

### Системные требования
1.	C++17 (STL)
2.	GCC (MinGW-W64) 12.2.0

