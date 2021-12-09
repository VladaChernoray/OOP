#Лабораторная работа № 2

1) Создать файл XML и соответствующую ему схему XSD.
(При разработке XSD использовать простые и комплексные типы, перечисления, шаблоны и предельные значения, обязательно использование атрибутов и типа ID)

2) Сгенерировать (создать) Java-класс, соответствующий данному описанию.
3) Создать Java-приложение для разбора XML-документа и инициализации коллекции объектов информацией из XML-файла. Для разбора использовать SAX, DOM и StAX парсеры. Для сортировки объектов использовать интерфейс Comparator.

4) Произвести проверку XML-документа с привлечением XSD.

5) Определить метод, производящий преобразование разработанного XML-документа в документ, указанный в каждом задании.

###Алмазный фонд. 
Драгоценные и полудрагоценные камни, содержащиеся в павильоне, имеют следующие характеристики:
* Name – название камня.
* Preciousness – может быть драгоценным либо полудрагоценным.
* Origin – место добывания.
* Visual parameters (должно быть несколько) – могут быть: цвет (зеленый, красный, желтый и т.д.), прозрачность (измеряется в процентах 0-100%), способы огранки (количество граней 4-15).
* Value – вес камня (измеряется в каратах). Корневой элемент назвать Gem.