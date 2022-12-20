# KiberImun
# 2 задание

Сформулировать ЦПБ для системы "Информационная система" (Автоматизированный журнал машиниста)
(мы хотим достичь такого состояния системы, при котором злоумышленник не может изменить информацию , которая попадает в журнал и оттображается машинисту для того, чтобы он принял поезд и выдвинулся по маршруту)

## _Цель_: 

а) Ни при каких обстоятельствах не должно быть расхождений между введеной информацией в электронный журнал локомотивной бригадой и информацией, которая отображается в приложении машинисту

б) получение задания только от легитимного сервера

в) противодействие от взлома мобильного приложения с условием физического доступа

## _Предположения безопасности_

защита от намеренного искажения информации поступающей в журнал

сервис "Монитор безопасности" является полностью доверенным 

обмен сообщениями через сервис "Шина сообщений" надежно защищен от любого взлома


