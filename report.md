# Отчёт о тестировании Precision

## Краткое описание

<2021.05.11 at 10:00 PM> - <2021.05.11 at 11:00 PM> было проведено тестирование методом White Box приложения **Precision**.

На тестирование затрачено: <1 час>

В результате тестирования выявлены следующие дефекты:
* [Значение оператора сложение ошибочно при работе с данными типа double](https://github.com/Alexandra-Matyukhina/Precision/issues/1#issue-888457527)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* IntelliJ IDEA Community Edition

В качестве тестовых данных использовался код приложения **Precision**:
* double regularBonus = 0.3;
  double specialBonus = 0.6;
  double totalBonus = regularBonus + specialBonus; **Exp.result is 0.9**


Тестирование производилось в следующем окружении:
* Устройство: Microsoft Surface Laptop 3
* Windows 10
* AdoptOpenJDK JDK with Hotspot 11.0.10+9 (x64)
* IntelliJ IDEA 2021.1.1 (Community Edition), Runtime version: 11.0.10+9-b1341.41 amd64