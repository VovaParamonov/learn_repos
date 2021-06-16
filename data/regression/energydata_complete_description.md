# Data set: Energydata_complete 

[Источник](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction)

The data for regression tasks

The data set is at 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods. The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column. Two random variables have been included in the data set for testing the regression models and to filter out non predictive attributes (parameters).
## Attribute information

date time year-month-day hour:minute:second

Appliances, используемая энергия в Ват/час 

lights, использование энергии светильников в доме 

T1, Температура в кухонной зоне, в градусах Цельсия

RH_1, Влажность в кухонной зоне, в %

T2, Температура в гостиной, в градусах Цельсия

RH_2, Влажность в зоне гостиной, в %

T3, Температура в зоне прачечной

RH_3, Влажность в зоне прачечной, в %

T4, Температура в офисном помещении, в градусах Цельсия

RH_4, Влажность в офисном помещении, в %

T5, Температура в ванной комнате, в градусах Цельсия

RH_5, Влажность в ванной комнате, в %

T6, Температура снаружи здания (северная сторона), в градусах Цельсия

RH_6, Влажность снаружи здания (северная сторона), в %

T7, Температура в гладильной комнате , в градусах Цельсия

RH_7, Влажность в гладильной комнате, в %

T8, Температура в комнате для подростков 2, в градусах Цельсия

RH_8, Влажность в комнате для подростков 2, в %

T9, Температура в комнате родителей, в градусах Цельсия

RH_9, Влажность в родительской комнате, в %

To, Температура снаружи (от метеостанции Кьевр), в градусах Цельсия

Pressure (от метеостанции Кьевр), в мм рт. ст.

RH_out, Влажность снаружи (от метеостанции Кьевр), в %

Wind speed, м/с

Видимость, в км

Tdewpoint, ° C

rv1, Случайная величина 1, безразмерная

rv2, Случайная величина 2, безразмерная


Там, где указано, почасовые данные (затем интерполированные) с ближайшей метеостанции аэропорта (аэропорт Кьевр, Бельгия) были загружены из общедоступного набора данных из Надежного прогноза, rp5.ru. Разрешение было получено из Достоверного прогноза для распределения данных о погоде за 4,5 месяца.