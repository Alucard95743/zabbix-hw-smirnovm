# Домашнее задание : Система мониторинга Zabbix. Часть 2
**Студент:** Смирнов Михаил

## Задание 1

На скриншотах представлена реализация шаблона для мониторинга загрузки CPU и RAM в процентах. На втором скриншоте указаны используемые ключи элементов данных (items), подтверждающие корректность сбора метрик.

![Задание 1](https://raw.githubusercontent.com/Alucard95743/zabbix-hw-smirnovm/main/img/task1.png)

![Задание 1](https://raw.githubusercontent.com/Alucard95743/zabbix-hw-smirnovm/main/img/task1.1.png)

---

## Задание 2+3

Скриншот подтверждает назначение шаблонов на виртуальные машины. Видно, что к хостам применены оба требуемых шаблона: созданный ранее `Custom CPU RAM Monitoring` и стандартный `Linux by Zabbix agent`. Это обеспечивает сбор всех необходимых метрик с обеих ВМ.

![Задание 2+3](https://raw.githubusercontent.com/Alucard95743/zabbix-hw-smirnovm/main/img/task2+3.png)

---

## Задание 4

На скриншоте представлен дашборд, отображающий агрегированные метрики по созданному шаблону. Видны графики загрузки CPU и RAM с обеих виртуальных машин (`smirnovmi-1` и `smirnovmi-2`), что подтверждает работоспособность сбора данных и визуализации.

![Задание 4](https://raw.githubusercontent.com/Alucard95743/zabbix-hw-smirnovm/main/img/task4.png)
