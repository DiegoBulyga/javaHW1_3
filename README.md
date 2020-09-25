# Отчёт о тестировании приложения "Money Transfer"

## Транзакция "Пополнение счета клиента"
* Текущий баланс счёта клиента - два миллиарда рублей (Int);
* Сумма перевода - пятьсот миллионов рублей (Int);
* Переменная для хранения итогового значения - тип int.

## Unit test "Запуск кода"

## В результате тестирования выявлены следующие дефекты:
![](https://raw.githubusercontent.com/BulygaDenis/javaHW1_3/master/1.4.png)


## Результаты

1. 0/1
2. [issues #1](https://github.com/BulygaDenis/javaHW1_3/issues/1)


**Ожидаемый результат:**
2500000000
**Фактический результат:**
-1794967296

## Общие рекомендации:
Использовать для `total` другой тип переменной.

## Окружение:

Win 10 x 64

openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)



