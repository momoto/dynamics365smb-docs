# Практическое руководство. Создание товарного отчета ТОРГ-29

В отчете ТОРГ-29 показываются товарные документы, которые можно использовать для отправки приходных и расходных накладных для склада. 

После формирования этого отчета для склада поля **Номер последнего отчета по товарам** и **Номер последнего отчета по товарам** в окне **Карточка склада** обновляются для обеспечения согласованной отчетности.

 

## Создание отчета ТОРГ-29 

1. Выберите значок ![Поиск страницы или отчета](https://github.com/DianaMalina/dynamics365smb-docs/blob/live/business-central/LocalFunctionality/Russia/1.png), введите **Товарный отчет ТОРГ-29**, а затем выберите связанную ссылку.

2. На экспресс-вкладке **Параметры** заполните поля, как описано в следующей таблице.

   | Поле                                           | Описанием                                                    |
   | :--------------------------------------------- | :----------------------------------------------------------- |
   | **Код Склада**                                 | Определяет склад, для которого предназначен отчет.           |
   | **Номер отчета**                               | Определяет количество раз, которое отчет был напечатан, на основе значения поля **Номер последнего отчета по товарам** в окне **Карточка склада**. |
   | **Материально-ответственное лицо**             | Определяет сотрудника, ответственного за правильность данных в отчете. |
   | **Приемщик отчета**                            | Определяет сотрудника, ответственного за приему отчета.      |
   | **Дата отчета**                                | Определяет дату отчета.                                      |
   | **Дата Начала**                                | Определяет дату начала для отчета.                           |
   | **Дата Конца**                                 | Определяет дату начала для отчета.                           |
   | **Тип операции**                               | Определяет тип операции (необязательно). Эта информация будет включена в отчет. |
   | **Номера приложений**                          | Определяет количество приложений к отчету.                   |
   | **Детализация приемки**                        | Определяет, на каких подробных сведениях основана каждая операция.   Если выбрано значение **Документ**, значения суммируются по каждому документу. Если выбрано значение **Товар**, сумма и количество суммируются по каждому товару. Если выбрано значение **Операция**, то сумма и количество включаются в отдельную транзакцию. |
   | **Детализация отгрузки**                       | Определяет, на каких подробных сведениях основана каждая операция.   Если выбрано значение **Общая сумма**, то все суммы в отчете объединяются в одну строку. Если выбрано значение **Документ**, значения суммируются по каждому документу. Если выбрано значение **Товар**, сумма и количество суммируются по каждому товару. Если выбрано значение **Операция**, то сумма и количество включаются в отдельную транзакцию. |
   | **Тип Суммы**                                  | Определяет, на чем основаны суммы — на стоимости или цене продажи.   Если в этом поле выбрано значение **Цена продажи**, становятся доступными поля **Тип продажи**, **Показать сумму себест. для прих. накладных**, и **Показать сумму себест. для расх. накладных**. |
   | **Тип продажи**                                | Определяет тип прайс-листа.   Если выбрано значение **Прайс-лист клиента** или **Кампания**, прайс-лист можно выбрать в поле **Код продажи**. Если выбрано значение **Все клиенты**, используется единый прайс-лист. |
   | **Код продажи**                                | Определяет прайс-лист. В зависимости от значения в поле **Тип продажи** можно определить номер кампании или ценовую группу клиентов. |
   | **Показать сумму себест. для прих. накладных** | Определяет, должна ли каждая приходная накладная делиться на две строки. Если выбрано, первая строка приходной накладной представляет стоимость товара, а вторая — прибыль от продаж. |
   | **Показать сумму себест. для расх. накладных** | Определяет, должна ли каждая расходная накладная делиться на две строки. Если выбрано, первая строка приходной накладной представляет стоимость товара, а вторая — прибыль от продаж. |

3. Нажмите кнопку **Печать**.

 

## См. также 

[Настройка запасов](https://docs.microsoft.com/ru-ru/dynamics365/business-central/inventory-setup-inventory)
