## Міні проєкт "Щаслива родина" (продовження)

Суть проєкту: опис структури сім'ї з урахуванням того, що кожна людина має кровних родичів, а склад сім'ї може з часом змінюватися.

## Робота з датою та часом

## Завдання

Удоскональте проєкт: Зробіть рефакторинг класу `Human` так, щоб він працював з датою та часом.

#### Технічні вимоги:
- Замініть поле `year` на поле `birthDate` яке зберігає значення Unix Millis Timestamp (тип `long`).
- Додайте в клас `Human` метод `describeAge()`, який повертає рядок, що вказує точну кількість років, місяців та днів життя людини;
- Створіть конструктор для усиновлених дітей, що описує ім'я, прізвище, дату народження та IQ. Дата народження передається у вигляді рядка у форматі `20/03/2016`
- Зробіть рефакторинг методу `toString()` щоб він замість року народження вказував дату народження у форматі `20/03/2016`

#### Література:
- [Period для розрахунку інтервалів між датами](https://www.baeldung.com/java-period-duration)
- [Java 8 New Date/Time API - Частина 1](https://dan-it.gitlab.io/fs-book/java-basic/ext/ext_newDate_and_TimeAPI_part1/ext_newDate_and_TimeAPI_part1.html)
- [Java 8 New Date/Time API - Частина 4](https://dan-it.gitlab.io/fs-book/java-basic/ext/ext_newDate_and_TimeAPI_part4/ext_newDate_and_TimeAPI_part4.html)
- [Creating a LocalDate with Values in Java](https://www.baeldung.com/java-creating-localdate-with-values)
