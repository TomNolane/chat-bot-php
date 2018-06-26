# chat-bot-php

very simple chat bot on php

Convet all words to big integer [from 0 to 1] and and comparing with $s2 as a percentage (where 100% is not maximum)

Just copy bot.php and open in LAMP/XDebug/Web Page

##It's show  next results:

мне нужно займ - хотел бы получить займ : 41%
мне нужен займ - хотел бы получить займ : 41%
мне нужен заим - хотел бы получить займ : 0%
жене нужно займ - хотел бы получить займ : 38%
хотел бы найти займ - хотел бы получить займ : 131%
загрузить документы - хотел бы получить займ : 27%
хочу найти займ - хотел бы получить займ : 53%  

###Out mini phrases database:
```php array("мне нужно займ","мне нужен займ","мне нужен заим","жене нужно займ","хотел бы найти займ","загрузить документы","хочу найти займ");  ```  

###Incoming request:
```php array("хотел бы получить займ"); ```