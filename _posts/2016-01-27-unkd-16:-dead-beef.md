---
layout: post
title: УНКД 16: Dead Beef
date: {fullDate} 00:00:00 +0300
tags: [Imported]
---
# УНКД #16: Dead Beef

Dead beef является формой записи некоторых слов. При отладке компьютерных программ содержание памяти должно отображаться на экране (или, как это было в давние времена, на бумаге). Эта информация могла быть представлена в виде совершенно нечитаемого моря нулей и единичек.

Пример размером в почтовую марку мог выглядеть следующим образом:

> 00000001 10000101 10010101 00100010

Более удобно использовать шестнадцатеричную систему, состоящую из десятеричных цифр от 0 до 9 и латинских букв от A до F (A, B, C, D, E, F), которые применяются для обозначения чисел, в повседневной жизни обычно обозначаемых как 10, 11, 12, 13, 14 и 15\. Результат получается более читаемым. Хотя по-прежнему малопонятным для непосвященных:

> B290023F 72C70014 993DE110 8A01D329

Кодировщики всегда старались в этих нагромождениях, состоящих из цифр и букв, получить какие-то легко узнаваемые составляющие. Они обратили внимание на то, что некоторые числа, представленные в шестнадцатеричной системе, внешне напоминают английский слова, написанные заглавными буквами. Можно даже «произнести» любое слово или фразу, воспользовавшись первыми шестью буквами этого алфавита (иногда добавляя к нему 0 как О и 1 как прописную I). Вот несколько примеров таких «слов»: FEEDFACE, ABADBABE и, как вы уже догадались, DEADBEEF

Некоторые системы, используемые IBM и Apple Mac, периодически записывают в память DEADBEEF. Это сделано, чтобы сообщить о ситуациях, при которых в памяти происходят нарушения из-за программы, содержащей множество ошибок.

Если вы не видите ожидаемую DEADBEEF, то понимаете, что произошла какая-то серьезная ошибка.

DEADBEEF не является универсальным кодом; существует множество и других аналогичных «слов», используемых для этой же цели или каких-то других.

Источник:[ http://tproger.ru/problems/dead-beef/](http://tproger.ru/problems/dead-beef/)

Первоисточник: ["Are you smart enough to work at Google"](https://en.wikipedia.org/wiki/Are_You_Smart_Enough_to_Work_at_Google%3F)