# hw9
Чтобы выполнить задание, я пользовалась приложение Notepad++

*1. Удалить все пустые строки.*

Я использовала регулярное выражение \n\r и заменила на \0, таким образом, удалила все пустые строки.
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%201.jpg)

Однако, пустые строки все равно остались. Я решила, что в них есть пробелы, использовала регулярное выражение ^\s*$ и удалила пустые строки, в которых содержится только пробел. 
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%202.jpg)

*2. Найти всех князей и города, имя и название которых оканчивается на "слав".*

Я использовала регулярное выражение [А-Я]+\w+слав+\w+ чтобы найти имена князей и города, содержащих в себе "слав" (не те, которые оканчиваются, так как в примере написаны слова в которых есть окончания, например, Ростиславу). Итого получилось 592 вхождения. 
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%203.jpg)

*3. Найти все упоминания Новгорода. Учтите, что написание может быть разным.*

Я применила регулярное выражение (Новѣ?город[а-я]?|Новъ?город[а-я]?|Новгородц[а-я]?|Новагород[а-я]?|Новугород[а-я]?|Новгород[а-я]?) чтобы найти все упоминания Новгорода в летописи. У меня получилось 59 вхождений. 
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%204.jpg)

*Бонусное задание*

Бонусное задание я выполняла в несколько действий. По очереди вставляя пробелы после необходимых знаков препинания. 
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%205.jpg)
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%206.jpg)
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%207.jpg)
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%208.jpg)
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%209.jpg)
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%2010.jpg)
![](https://github.com/yuliatrakt/hw9/blob/master/изобр%2011.jpg)
