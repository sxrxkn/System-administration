## Занятие 7.

Системы мониторинга - это совокупность связанных компонентов для дистанционного получения и обработки данных от какого либо оборудования.

Что собирает система мониторинга:

- Потребление системных ресурсов
- Мониторинг внешних устройств
- Запуск/завершение работы программ
- Мониторинг потребления ресурсов серверами
- Мониторинг состояния оборудования
- Журналы (сбор информации о событиях в системе)

В чем смысл этого?:

- Дает информацию об использовании ресурсов оборудования
- информацию о событиях

Как эти данные использует человек?:

- Отслеживает текущее состояние системы
- История пользование системы (ошибки и тд). Отсюда вытекает третий пункт
- Прогноз на будущее системы

Какие системы мониторинга бывают:

- оперативные - получают данные сразу
- локальные - получаю данные с задержкой
- централизованные - получают данные с задержкой. Собирают в едином месте данные с множества систем.

ПО для мониторинга: 

- Оперативное (task, scheduler, top)
- Локальные (monit, munin netdata)
- Централизованные (zabbix)