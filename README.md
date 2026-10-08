# Markdown (гайд, основанный на нигерах и парнухе)
## Заголовки  и разделы 

```markdown
# 1 nigga
```
# 1 nigga

```markdown
## 2 nigga
```
## 2 nigga

```markdown
### 3 nigga
```
### 3 nigga

```markdown
#### 4 nigga
```
#### 4 nigga

```markdown
##### 5 nigga
```
##### 5 nigga

```markdown
###### 6 nigga
```
###### 6 nigga

```markdown
0 nigga
```
0 nigga

```
Цифра указыавет на количество # перед словом
```

#### Текст автоматически подгоняется под выделенное поле (длина строк и их количество) (поизменяй размер окна, чтобы увидеть, как подгоняется текст)

nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga nigga



nigga nigga  \
\
##### без спецсимволов промежуток 1 и более свободная строка будет отображаться как одна строка (между строкой выше и строкой еще выше в редакторе промежуток 3 строки, но отображается как одна)
\
\
\
nigga
\
\
nigga nigga
\
\
\
nigga nigga 
\
\
##### Чтобы сделать подобные разрывы, нужно в каждую свободную строку вписать " \ " (обратный слеш)


## Форматирование текста (_ / * и ~~)

### Жирный шрифт
```
**слово**
```
```markdown
__nigga nigga__
**nigga nigga**
```
Результат: \
\
__nigga nigga__ \
**nigga nigga**

### Курсив
```
*слово*
```
```markdown
_nigga nigga_
*nigga nigga*
```
Результат: \
\
_nigga nigga_ \
*nigga nigga*

### Зачеркнутый
```
~~слово~~
 ```
 ```markdown
 ~~nigga nigga~~
 ```
 Результат: \
\
~~nigga nigga~~

### Всё сразу 
```
~~***слово***~~
```
```markdown
~~___nigga nigga___~~
~~***nigga nigga***~~
```
Результат: \
\
~~___nigga nigga___~~ \
~~***nigga nigga***~~

### Подчернкнутый
```
<u>слово</u>
```
```markdown
<u>nigga nigga</u>
```
Результат: \
\
<u>nigga nigga</u>

## Цвет 
```markdown
<span style="color:#c0392b">red text nigga</span>
```
Результат: \
\
<span style="color:#c0392b">red text nigga</span>

```
<span style="color:#c0392b">__текст__</span>
для красного цвета, если нужен дпугой цвет, то в поле после "color:" вписать необходимое кодовое наименование
```

## Комментарий
```markdown
<!-- comment -->
```

## Списки

### Точечный:

#### Чтобы сделать точечный список, нужно начинать каждую строку с " - "," * "," + "; чтобы сделать подпункты необходимо делать отсупы от главного пункта 2 или 4 пробела
\
Наример:
```markdown
* nigga
  * nigga
    * nigga
* nigga
  * nigga
    * nigga
* nigga
  * nigga
    * nigga
```
Результат: 


* nigga
  * nigga
    * nigga
* nigga
  * nigga
    * nigga
* nigga
  * nigga
    * nigga

### Нумерованый:

#### Чтобы сделать нумерованный список, нужно начинать каждую строку с " 1. "," 2. "," 3. " и тд
\
Например:
```markdown
1. nigga
2. nigga
3. nigga
```
Результат: 


1. nigga
2. nigga
3. nigga

## Ссылки
```markdown
<ссылка>
```
Например:
```markdown
<https://pornhub.com>
```
Результат: \
\
<https://pornhub.com>

## Показ слов вместо ссылки
```markdown
[Показываемый текст](ссылка)
```
Например:
```markdown
[Кликни чтобы парнуха](https://porhhub.org)
```
Результат: \
\
[Кликни чтобы парнуха](https://porhhub.org)

## Показ слов вместо ссылки и показ текста при наведении на ссылку
```markdown
[Показываемый текст](ссылка "Текст при наведении")
```
Например:
```markdown
[Наведи или кликни чтобы парнуха](https://pornhub.com "Парнуха")
```
Результат: \
\
[Наведи или кликни чтобы парнуха](https://pornhub.com "Парнуха")

## Относительные ссылки
```
[Относительная ссылка][переменная] и [вторая ссылка, ведущая туда же][переменная]
--Пропуск строки--
[переменная]: ссылка непосредственно на сайт
``` 

Наример:
```markdown
[Ссылка на парнуху][парнуха] и [еще одна ссылка на парнуху][парнуха]

[парнуха]: https://pornhub.com 
```
Результат: \
\
[Ссылка на парнуху][парнуха] и [еще одна ссылка на парнуху][парнуха]

[парнуха]: https://pornhub.com 

## Картинки
```markdown
![описание(если не загрузит картинку) ](файл картинки/ссылка на картинку "Подсказка при наведении")  (подсказка необязательна)
```
Пример без подсказки:
```markdown
![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10)
```
Результат: \
\
![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10) 
\
\
И пример с подсказкой:
```markdown
![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10 "nigger")
```
Результат: \
\
![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10 "nigger") \
__Наведи курсор на картинку__

## Кликабельные картинки со ссылками
```markdown
[![Текст](файл картинки/ссылка на картинку)](ссылка)
```
Пример без подсказки:
```markdown
[![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10)](https://pornhub.com)
``` 
Результат: \
\
[![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10)](https://pornhub.com) \
__Нажми на картинку__ \
\
\
И пример с подсказкой:
```markdown
[![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10 "nigger")](https://pornhub.com)
```
Результат: \
\
[![nigger](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT48rT5WciUaSQr5KGEQCAAqMsueZxlB7oc0yh0ZgmHug&s=10 "nigger")](https://pornhub.com) \
__Наведи курсор и нажми на картинку__ 


## Код 
```
Если нужно обозначить какой-то участок в строке, то его нужно с двух сторон заключить в обратные кавычки " ` ";

А если нужно обозначить нескоько строк, то использовать следующую конструкцию:
```язык_программирования ; 
со следующей строки писать код ; 
и в конце, под кодом, на следующей строке написать " ``` "

То есть, заключить его в три обратных кавычки сверху и снизу
```

```
Если не указывать язык программирования, то получится просто текст в отдельном поле
```

#### Пример конструкции: 

```markdown
Use the `print()` function. 
```
```markdown
```python 
def wazzup(nigga): 
  return f"Wazzup {nigga}" 
```\
```

Получится: \
\
Use the `print()` function
```python 
def wazzup(nigga):
  return f"Wazzup {nigga}"
```
Код сверху ограничен такой конструкцией: ` ```python ` - т.е. начало блока кода и указание языка, а снизу: ` ``` ` - конец блока кода

## Цитаты 
```
Чтобы сделать цитату, в начале строки необходимо поставить ">";
Если нужно сделать цитату в цитате, использовать "> >" или больше стрелок (по необходимости)
```
#### Примеры конструкций:
```markdown
> nigger
> > nigger
> > > nigger
```
Такая конструкция будет иметь вид:
> nigger
> > nigger
> > > nigger

#### Если в конце строки не ставить "`\`", то текст будет форматироваться как одна строка и будет масштабирваться (подгояться под размер окна), если нужно сделать абцаз, то в конце строки необходимо добавить "`\`"
#### Примеры конструкций:
```markdown
> nigger
> nigger
> nigger
```
Будет иметь вид:
> nigger
> nigger
> nigger

**В свою очередь:**
```markdown
> nigger \
> nigger \
> nigger
```
Будет иметь вид:
> nigger \
> nigger \
> nigger

## Тематические разделения (линии между абзацами)
```
"***" , "---" , "___" - 3 и более символа, расположенные на отдельной строке создают полосу разделения
```
#### Пример конструкции:
```
---

nigger

***

nigger

___

nigger

---
```
__Будет иметь вид:__

---

nigger

***

nigger

___

nigger

---

## Отображение спецсимволов
```
Некоторые символы, по типу: " \ ", " ` "," # " [ " являются командами, 
и если необходимо отобразить такой символ, 
то перед ним необходимо поставить " \ " - обратный слеш; 
(один слеш покрывает только один символ!)
```
#### Примеры конструкций:
`\*` -> \* \
`\#` -> \# \
`\*#` -> \*#

`\**nigger**` -> \**nigger** (вторая звездочка не считается спец символом, поэтому вместо "**nigger**" отображается "*nigger*" )
