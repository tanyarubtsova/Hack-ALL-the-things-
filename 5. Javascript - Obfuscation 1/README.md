1) Переходим по адресу http://challenge01.root-me.org/web-client/ch4/ch4.html
2) Видим поле для ввода пароля
3) Нажимаем клавиши Ctrl+Shift+i, внизу страницы открываем файл ch4.html
4) Видим строчки
pass = '%63%70%61%73%62%69%65%6e%64%75%72%70%61%73%73%77%6f%72%64';
h = window.prompt('Entrez le mot de passe / Enter password');
if(h == unescape(pass))
То есть надо ввести значение unescape(%63%70%61%73%62%69%65%6e%64%75%72%70%61%73%73%77%6f%72%64), которое можно посчитать, запустив программу на JS, выводящую это значение
Вводим соответствующее значения в поле
5) WIN
