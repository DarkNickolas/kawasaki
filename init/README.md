# Практикуємось з Markdown
### Форматування тексту та робота з списками
1. Ми пробуємо виділити текст *курсивом* або _він ще називається Італік_;
1. Також можна виділити **жирний текст**. __Це також буде жирним__;
    - Можна поєднувати форматування тексту **та серед жирного тексту _вставляти текст курсивом_**;
    + Ми навчились форматувати текст, ~~місія комплітед~~ :white_check_mark: ;

---

### Практикуємось з лінками та вставленням скріншотів
- Пробуємо вставити посилання [на сайт ІТ коледжу Львів](https://itcollege.lviv.ua/ "Перехід на головну сторінку сайту");
- [Перехід на кореневий файл README](../README.md);
- ![тут буде відображатись картинка](https://github.com/BobasB/2023_tk41_oop/raw/main/init/pictures/logo-lit.jpg "Не забуваємо замінити blob на raw") VS ![тут може бути будь-який текст](pictures/logo-lit.jpg)

---

### Робота з частинами коду
- Код можна всталяти просто як текст (так вставляти код неправильно):

    def greet(name):
        print(f"Hello, {name}!")

- Вставляємо код через блоки з підсвіткою синтаксису (так робити правильно):
    ```python
    def greet(name):
        print(f"Hello, {name}! Using Python")
    ```
    - можна підсвічувати різні мови програмування, наприклад Java або якісь застарілі вмови типу Pascal:
    ```java
    public class HelloWorld {
        public static void main(String[] args) {
            System.out.println("Hello, world! on Java");
        }
    }
    ```
    ```pascal
    program HelloWorld;
    begin
      writeln('Hello, world!');
    end.
    ```
    ```bash
    echo "Hello World on Bash"
    ```
---

### Експериментуємо з виносками
Це є текст до якого ми добавимо виносу на сайт ІТ коледжу з розкладом[^link].

[^link]: https://itcollege.lviv.ua/rozklad-1-sem-23-24/

---

### Робота з таблицями
> Робота з таблицями передбачає що буде рядок заголовків, відділювальний рядок де ми вказуємо позицію тексту в комірках та власне рядки з даними таблиці.

| Лого навчального закладу | Група | Персона |
|---|:---:|---:|
| ![logo](pictures/logo-lit.jpg) | ТК-41 | Богдан |
| - | - | - |

---
