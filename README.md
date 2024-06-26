# Техническое задание: основные метрики для email рассылок
[Дашборд](https://datalens.yandex.cloud/akmxujbdhj5wy-mailfit)

[ipynb](https://github.com/lisaryap/Assessment-Tests/blob/main/Email_metrics.ipynb)

## Описание проекта

На основе тестового набора данных необходимо посчитать следующие метрики:

- Delivery rate,
- Open rate,
- Click to Open rate,
- Unsubscribe rate.
Также нужно выявить лучшие темы писем и лучший день недели для планирования рассылок.

## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **seaborn**
- **scipy**
- **DataLens**

## 

## Общий вывод

Самые высокие показатели Open rate были у писем с темами "Тема письма1" и "Тема письма 101".

Больше писем открывают в среду, но по ссылкам переходят больше во вторник. Однако нельзя однозначно выделить лучший день недели для отправки рассылок, так как различие метрик Open rate и CTOR для этих дней не имеет статистически значимого отличия от других дней.
