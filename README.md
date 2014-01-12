# Антимат

Простая система защиты от матерных слов. Отвечает на вопрос, содержит ли сообщение мат

## Usage

Загрузить библиотеку. Никаких зависимостей не требуется.

```html
<script src="antimat.js" type="text/javascript"></script>
```

Теперь можно использовать специальный метод:

```html
<script type="text/javascript">
   var message = ""; // get from somewhere
   if(window.containsMat(message)){
      // obscene detected
   }
</script>
```

## Ссылки
[Пишем простой антимат для чата](http://www.itlessons.info/javascript/simple-obscene-checker/)

## Автор

[itlessons](http://www.itlessons.info) ([@itlessonsinfo](http://twitter.com/itlessonsinfo))

## Лецензия
[MIT License](http://www.opensource.org/licenses/mit-license.php)