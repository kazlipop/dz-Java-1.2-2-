Неверное значение в итогах кода

1) Берем код из данных для Задача №2 - Precision

public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

2) Копируем его в idea
3) C помощью сочетания клавиш shift+f10 запускаем код
4) В открывшейся строке сверяем данные

Ожидаемый результат: 0.9

Фактический результат:  0.8999999999999999;

Окружение:
* Windows 10 Pro x64
* Java SE 11.0.1

ссылка на исходники проекта на GitHub;
