# Туториал по языку разметки Markdown

## Как добавить заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести.
Например:

# Header1
## Header2
### Header3
#### Header4
##### Header5
###### Header6

## Как добавить исходный код

чтобы добавить исходный код, необходимо использовать конструкцию следующего вида:
```html
<table>
	<tr>
		<td style="color:#ffd700">
			Text
		</td>
	</tr>
</table>
```
Пример рабочего кода без кавычек:
<table>
	<tr>
		<td style="color:#ffD700">
			Text
		</td>
	</tr>
</table>

## Как добавить таблицы

Таблицы не являются частью Markdown, но многие обработчики, например Markdown Here и Github, поддерживают их.

| Таблицы       | Это                | Круто |
| ------------- |:------------------:| -----:|
| столбец 3     | выровнен вправо    | $1600 |
| столбец 2     | выровнен по центру |   $12 |
| зебра-строки  | прикольные         |    $1 |

Markdown | не такой | красивый
--- | --- | ---
*Но выводится* | `тоже` | **не плохо**
1 | 2 | 3

## Как добавить изображения

**Чтобы добавить изображение в разметку MarkDown, используйте следующую конструкцию:**
```
![альтернативный текст](ссылка на изображение)
```
Пример:
![аниме пачаны](https://awesomereviews.ru/wp-content/uploads/2018/10/Веселье-752x440.jpg)

Чтобы добавить картинку ссылку, необходимо модифицировать блок_схему сверху следующим образом:

```
[1[альт.текст](ссылка на изображение)](ссылка на изображение на которую будет переброс)
```

Пример:
[![прикол](https://www.meme-arsenal.com/memes/02992f294c7347a29a428fe4e62ab53f.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)