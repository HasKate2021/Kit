# Инструкция

========================

#  Заголовки:

#  Заголовок первого уровня

### Заголовок третьего уровня

###### Заголовок шестого уровня
=========================

## Написание текстов

*курсив*  _текст_ 

**жирный** __текст__ 

***жирный*** ___курсив___ 

=========================

## Списки
* элемент1
* элеиент2
- элемент3
+ элемент4

1. элемент1
    * подэлемент а
    * подэлемент б
2. элемент2 

=========================
## Цитаты

>цитата 
>>цитата в цитате
>>>и снова 
>
>там был пропуск строки
и так можно

1. вариант 1 
    >цитата в списке

***
---
## Исходный код

1. исходный код в списке

        исходный код с двумя табуляциями 
        
2. дополнение

        каждую строку параграфа
        начинать с одного символа
        табуляции. продолжается пока
        не встретится строка без 
        отступа.  
        внутри блоков кода обычный 
        синтаксис Markdown не 
        обрабатывается.

3.  `позволяет поместить код внутрь обычного абзаца текста`

## ССылки        

1. ссылка
    [Текст](https://vk.com/feed/ "всплывающая необязательная подсказка")
2. вместо целевого адреса       используется вторая пара квадратных скобок, внутри которых помещается метка, идентификатор ссылки   
    [пример][id]
    [Текст] [id]
В этом случае возможно определить идентификатор в любом месте документа:
    [id]: http://example.com/ "Необязательная подсказка" 
    [текст ссылки][a]
    [текст ссылки][A] 
3. неявно выраженный идентификатор -метка не приводится, текст гиперссылки используется и в качестве её имени, а вторая пара квадратных скобок остаётся пустой. Например, чтобы сделать слово «Example» гиперссылкой, ведущей на сайт http://example.com/, достаточно написать:
    [Example][] 
и затем определить гиперссылку:

[Example]: http://example.com/ 

4. <http://example.com/> просто ссылка

## Картинки

1. ![альтернативный изображению текст станет содержимым атрибута в элементе img](https://sun9-48.userapi.com/impg/KdWCFheovNKk_xQ94-lMqqRihKLsSqXBVTRJ0w/RgXaxoYN32g.jpg?size=604x404&quality=96&sign=d4bfb444f9fa2d374c1a0b51a804257a&type=album "Необязательная подсказка")
2. ![Альтернативный текст][id]

    [id]: https://365psd.com/images/thumbs/bb1/flecha-arrow-52197.png "Необязательная подсказка"

