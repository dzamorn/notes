# Конспект

## Позиционирование элементов

Нормальная позиция (по умолчанию):

```stylus
position static
```

Абсолютная позиция:

```stylus
position absolute
```

Фиксированная позиция:

```stylus
position fixed
```

Относительная позиция:

```stylus
position relative
```

## Начальный сброс отступов

```stylus
body
  margin 0
  padding 0
```

## Изменение цвета

Фоновый цвет:

```stylus
background #ff1244
background-color #ff1244
```

Цвет текста:

```stylus
color #ff0000
```

## Изменение шрифта

Шрифт:

```stylus
font-family Arial
```

Размер текста:

```stylus
font-size 20px
```

Жирность текста:

```stylus
font-weight normal // Обычный текст
font-weight bold // Жирный текст
```

## Типы элементов

Блок:

```stylus
display block
```

Строковой блок:

```stylus
display inline-block
```

Строковой элемент:

```stylus
display inline
```

## Блочная модель

### Внешние отступы

```stylus
margin 10px
margin 10px 20px // По вертикали и по горизонтали
margin 10px 20px 30px 40px // Отступы со всех сторон по часовой стрелке (начиная сверху)

margin-left 10px
margin-right 10px
margin-top 10px
margin-bottom 10px
```

### Граница

```stylus
border 1px solid #ff1111 // Толщина линии, тип линии, цвет линии

border-left 1px solid #ff1111
border-right 1px solid #ff1111
border-top 1px solid #ff1111
border-bottom 1px solid #ff1111
```

Типы границ:

* `solid`: Обычная линия.
* `dotted`: Точечная линия.
* `dashed`: Линия прочерками.
 
### Внутренние отступы

```stylus
padding 10px
padding 10px 20px // По вертикали и по горизонтали
padding 10px 20px 30px 40px // Отступы со всех сторон по часовой стрелке (начиная сверху)

padding-left 10px
padding-right 10px
padding-top 10px
padding-bottom 10px
```
