# Интеграция с Roistat
Интеграция с Roistat позволяет передавать данные по звонкам клиентам, совершенных с помощью CallKeeper.

На основании этих данных в Roistat автоматически cоздаются заявки. Если в проекте Roistat подключена интеграция с CRM, заявки отправляются в подключенную CRM.

[Инструкция по настройке интеграции на сайте ROISTAT](https://help.roistat.com/integrations/Servisy_obratnogo_zvonka/Callkeeper/?rs=partners_article_callkeeper_parthershipforsaas_17052019)

Вы можете отправлять в ROISTAT webhook по факту звонка с сайта, который также содержит cookies Roistat c их идентификатором сессии посетителя (который заказал и у которого прошел звонок с сайта, кроме звонков через API и с помощью метода FormAction).
Для этого в ЛК CallKeeper зайдите в раздел «Профиль» и включите тумблер «Собирать данные».
