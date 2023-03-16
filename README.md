# Инструкция по оформлению текста в Git при помощи языка markdown
___

## Работа с текстом
#### Для работы и выделения с текстом приняты следующее оформление:
1. *Курсив* 
Для оформления текста курсивом обрамляют текст с обоих сторон подчеркиванием \_так_ или звездочками \*так*
2. **Жирный текст**
   Для оформления текста жирным обрамляют текст с обоих сторон двумя подчеркиванием \_ _ так _ _ или звездочками \** так **
3. ***Жирный курсив***
   Для оформления текста жирным курсивом обрамляют с обеих сторон тремя подчеркиванием \_ _ _ так _ _ _ или звездочками \*** так ***
4. <u>Текст по стандарту html</u>
   Кроме языка markdown в описательной части можно применять язык html
    <p>Это <b>выделенный</b> текст</p>
    <p>Это <strong>важный</strong> текст</p>
    <p>Это <del>зачеркнутый</del> текст</p>
    <p>Это <s>недействительный</s> текст</p>
    <p>Это <em>важный</em> текст</p>
    <p>Это текст <i>курсивом</i> </p>
    <p>Это <u>подчеркнутый</u> текст</p>
    <p>X<sub>i</sub> = Y<sup><small>2</small></sup> + Z<sup><small>2</small></sup></p>




## Работа со ссылками

##### При работе со ссылками мы можем просто прописать сайт gb.ru или оформить ее с помощью кода
[X] (Y) 
где X это текст которы будет отображаться в инструкции/описании
где Y это ссылка на ресурс
Вфглядит это [так](gb.ru)



## Работа с картинками
Здесь будет оформление коартинок
#### Для отображения картинки необходимо прописать следующий код
\! [ X ] (Y "z") без пробелов, где:
* X описание картинки при невозможности ее отображения
* Y ссылка на картинку
* Z имя которое будет отображаться при наведении мышкой на картинку
![Лейбл GeekBrains](https://avatars.dzeninfra.ru/get-zen_doc/40170/pub_5abb9ec03dceb786201e3a8d_5abb9ed0c3321b184796c838/scale_1200 "Одна из икогок GB.ru")

#### Если картинка лежит в репозитарии проекта то место Y и Z прописывается путь к данному изображению:
\! [ X ] (img.jpg) Путь может быть какк в корневой дирректории так и в другой папке

![картинка в репозитариии](gb.png)

#### Так же можно сделать ссылку кликабельной, т.е. вставить ссылку на сайт в тело изображения

[![ссылка на ГБ](https://sun1-88.userapi.com/s/v1/if1/aBmRwrHe-h4dT7ViQHnTlw0zEjXUd_oMTp0R5BrlseqengGVWFcRBpkMHHTDZw_Esi4rsJKC.jpg?size=400x400&quality=96&crop=510,63,926,926&ava=1)](gb.ru)


## Работа со списками, чек-боксами, цитатами
Здесь будет оформление списков и т.д.


## Работа с таблицей


#### Для оформления таблиц используют следующее оформление

| LEFT           |  CENTER   |           RIGHT |
| :------------- | :-------: | --------------: |
| По левому краю | По центру | По правому краю |
| текст          |   текст   |           текст |

**Внимание:** Если в тексте таблицы нужно использовать символ "вертикальная черта - |", то в место него необходимо написать замену на комбинацию HTML-кода* \&#124;, это нужно для того, что бы таблица не потеряла ориентации.
*) - Можно использовать ASCII и/или UTF коды.

## Команды для Python
Здесь будут выложены список основных команд в Python
False - ложь
True - правда
None - "пустой" объект
and - логическое И
with / as - менеджер контекста
assert условие - возбуждает исключение, если условие ложно
break - выход из цикла
class - пользовательский тип, состоящий из методов и атрибутов
continue - переход на следующую итерацию цикла
def - определение функции
del - удаление объекта
elif - в противном случае, если
else - for/else или if/else
except - перехватить исключение
finally - вкупе с инструкцией try, выполняет инструкции независимо от того, было ли исключение или нет
for - цикл for
from - импорт нескольких функций из модуля
global - позволяет сделать значение переменной, присвоенное ей внутри функции, доступным и за пределами этой функции
if - если
import - импорт модуля
in - проверка на вхождение
is - ссылаются ли 2 объекта на одно и то же место в памяти
lambda - определение анонимной функции
nonlocal - позволяет сделать значение переменной, присвоенное ей внутри функции, доступным в объемлющей инструкции
not - логическое НЕ
or - логическое ИЛИ
pass - ничего не делающая конструкция
raise - возбудить исключение
return - вернуть результат
try - выполнить инструкции, перехватывая исключения
while - цикл while
yield - определение функции-генератора\

