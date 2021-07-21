# Отчёт о тестировании <Precision>
## Краткое описание
20.07.2021 - <Дата окончания> было проведено функциональное тестирование приложения на предмет перевода денег себе на счет VIP-клиентами организации.

На тестирование затрачено: 1 час

В результате тестирования выявлен следующий дефект:

[The bonus value is calculated incorrectly](https://github.com/vergizon/Hometask-2_2-java/issues/1) .


# Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:

Чек лист: https://github.com/netology-code/javaqa-homeworks/tree/master/programming (задача №2)

В качестве тестовых данных использовались данные:

- регулярный бонус клиент (переменная regularBonus типа double) - 0.6 ;
- специальный бонус клиента (переменная specialBonus типа double) - 0.3 ;
- переменная хранения итогового значения totalBonus типа double

'''
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

Тестирование производилось в следующем окружении:

версия и разрядность ОС - Windows 10 Pro x64; 
версия Java - 11.0.11;
другое ПО, при необходимости - IntelliJ IDEA version 2021.1.2