
# Отчёт о тестировании подсчёта бонусов
 
### Краткое описание

21.12.2020 было проведено тестирование  для проверки бонусной системы с помощью программы IntelliJ IDEA. 
На тестирование затрачено 2 часа 00 минут.

### В результате тестирования выявлены следующие дефекты:

[неверный подсчёт бонусов](https://github.com/NastiaZe/Precision/issues/1)  
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
1. код для проверки в IntelliJ IDEA. : 
     public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}



## Тестирование производилось в следующем окружении:

Micrsoft Windows 10 pro, версия: 1909 сборка 18363.418  
openjdk version "11.0.9.1" 2020.11.04