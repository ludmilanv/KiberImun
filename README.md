# KiberImun
# 1 задание

Сформулировать ЦПБ для системы "СКУД" (система контроля и управления доступом)
(мы хотим достичь такого состояния системы, при котором злоумышленник не смог бы попасть на территорию , 
те система СКУД обеспечивает валидный доступ на территорию)

## _Цель_: 

а)обеспечение доступа на территорию  авторизованным пользователям

б)обеспечение целостности данных между переваемыми компонентами СКУД

## _Предположения безопасности_

а) Все зарегистированные в системе пользователи не допускают потери пропусков ни намеренно, ни преднамеренно,по халатности или низкому уровню ИБ

б) данные, передающиеся между компонентами СКУД, ни при каких условиях не раскрываются для злоумышленника (неавторизованного пользователя).

## _Архитектура_ (очень обобщенно)

![Image alt](https://github.com/ludmilanv/{repository}/raw/{branch}/{path}/image.png)
