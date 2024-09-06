<p style="margin:0" align="center"><b>Министерство науки и высшего образования Российской Федерации</b></p>
<p style="margin:0" align="center">Федеральное государственное бюджетное образовательное учреждение высшего образования</p>
<p style="margin:0" align="center"><b>«Владимирский государственный университет 
имени Александра Григорьевича и Николая Григорьевича Столетовых»</b></p>
<p style="margin:0" align="center"><b>(ВЛГУ)</b></p>

 <p style="margin:0" align="center"><b>Колледж инновационных технологий и предпринимательства</b></p>


</p>
<p align="center">
КАФЕДРА ФИЗИКИ И ПРИКЛАДНОЙ МАТЕМАТИКИ
</p>
</br>
</br>
</br>
</br>
<p align="center" style="margin:0">
Лабораторная работа №1
</p>
<p align="center" style="margin:0">
по дисциплине «Инструментальные средства разработки программного обеспечения»
</p>
<p align="center" style="margin:0">
на тему: «Markdown»
</p>

</br>
</br>
</br>
</br>
<p align="right" style="margin:0">Выполнил:</p>
<p align="right" style="margin:0">студент группы ИПсп-121<p>
<p align="right" style="margin:0">Шарапова Е.В.</p>
<p align="right" style="margin:0">Принял:</p>
<p align="right" style="margin:0">Лоханов А.В.</p>
</p>

</br>
</br>
</br>
</br>

<p align="center" style="margin:50 0 50 0">
  Владимир, 2024 г.
</p>

   ---

   В ходе работы обращалась к:

   [![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white) [![DuckDuckGo](https://img.shields.io/badge/duckduckgo-de5833?style=for-the-badge&logo=duckduckgo&logoColor=white)](https://img.shields.io/badge/duckduckgo-de5833?style=for-the-badge&logo=duckduckgo&logoColor=white) [![Stack Overflow](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://img.shields.io/badge/-Stackoverflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white) [![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

   Авторство:
   
   [![Capitan](https://img.shields.io/badge/Capitan-blue?style=for-the-badge&link=https://github.com/CapitanWL?tab=overview&from=2023-12-01&to=2023-12-31)](https://github.com/CapitanWL?tab=overview&from=2023-12-01&to=2023-12-31)

   ---
   
   # Индивидуальное задание согласно варианту

   ## Оглавление


   1. [Оглавление](#оглавление)
   2. [Формулировка заданий](#формулировка-заданий)
      - [Формулировка индивидуального задания](#формулировка-индивидуального-задания)
   3. [Выполнение заданий](#выполнение-заданий)
      - [Выполнение индивидуального задания](#выполнение-индивидуального-задания)
   4. [Заключение](#заключение)

   ---

   **Цель работы:** Изучите основы работы с языком разметки Markdown, научитесь создавать и формировать текстовые документы.

   **Оборудование:** компьютер с установленным текстовым редактором, поддерживающим Markdown (например, Visual Studio Code, Atom, Sublime Text или онлайн-редакторы, такие как StackEdit, Dillinger).

   ## Формулировка заданий

   ### Формулировка индивидуального задания

   **Вариант 2**
   1. **Математические Формулы:** Вставьте формулу для вычисления площади круга.
   2. **Диаграммы с Mermaid:** Создайте диаграмму классов для простой системы.
   3. **Встроенный HTML:** Вставьте форму для отправки комментария.
   4. **Сложные Таблицы:** Создайте таблицу с выравниванием текста для списка студентов.
   5. **Галерея Изображений:** Вставьте три изображения городов.
   6. **Вложенные Списки:** Создайте план проекта с подзадачами.
   7. **Подсветка Синтаксиса:** Вставьте блоки кода на Java и C++.
   8. **Цитаты:** Вставьте цитату Стива Джобса.
   9. **Таблица Содержания:** Создайте автоматическую таблицу содержания.
   10. **Эмодзи и Специальные Символы:** Вставьте эмодзи для обозначения важной информации.

   ## Выполнение заданий

   ### Выполнение индивидуального задания

   1. Формула площади круга, $(S)$:
   $$ S = \pi{r^2} = \frac {\pi} {4} D^2 $$
   Где: $r$ - радиус круга, $D$ - диаметр круга, $\pi$ ≈ 3.14

   2. Диаграмма классов представлена ниже

   ```mermaid
   classDiagram 
   class Customer {
            + name: string
            + email: string
            + phone: string
            + author: string
            + Customer()
        }
        class Order {
            number: int
            timestamp: datetime
            products: List<Products>
            customer: Customer
            sum: decimal
            Order()
            AddProduct()
        }
        class Product {
            name: string
            category: string
            provider: Provider
            price: decimal

            AddElement()
            Product()
        }
        class Provider {
            company: string
            inn: string
            email: string
            phone: string
            address: string
            elements: [Product]
            
            Provider()
        }
        Customer --|> Order
        Provider --|> Product
        Product --> Product
        Product <--> Order
   ```

   3. Форма отправки комментария:
   <div class="sending-a-comment">

   <label for="user-email"><b>Введите ваш email</b></label>
   <input id="user-email" name="user-email" type="email" placeholder="Введите ваш email" required>

   <label for="comment-info"><b>Введите ваш комментарий</b></label>
   <textarea id="comment-info" rows="5" cols="30" placeholder="Введите ваш комментарий" name="comment-info" required></textarea>

   <button class="sendingbtn">Отправить комментарий</button>
   </div>

   4. Список студентов:

   |ФИО|Группа|Подгруппа|
   |:--|:----:|:-------:|
   |Иванов И.В|МРсп-121|1|
   |Петров И.Д|МДсп-121|2|
   |Сидоров А.В|Ипсп-121|1|
   |Малышев С.К|СДспк-121|1|
   |Сазонов И.И|МРсп-121|2|
   |Власов В.О|ИРспк-121|2|
   |Танишенко О.Л|ИРсп-121|2|
   |Грачев Г.Г|ТОсп-121|1|
   |Дмитров Д.Д|ТДсп-121|2|
   |Морозов М.М|СЗДспк-121|1|
   |Русков Р.Р|ИПспк-121|2|
   |Дроздов Д.С|ИПсп-121|1|
   |Портов П.П|МРсп-121|2|
    
   5. Изображения городов [^1]

   ![City 1](https://img.freepik.com/free-photo/observation-urban-building-business-steel_1127-2397.jpg?t=st=1725531500~exp=1725535100~hmac=52953797995767dd4020f8c86e857123065cb406d72f6d0c4487d80095e00548&w=900 "City 1")

   ![City 2](https://img.freepik.com/free-photo/shiny-night-city_1127-8.jpg?t=st=1725531952~exp=1725535552~hmac=f7e8bf5cea8012b3fad20c1938218e12fb1a3319e24bec8494ec2d15b15f4a18&w=900 "City 2")

   ![City 3](https://img.freepik.com/free-photo/view-new-york-city-usa_53876-153448.jpg?t=st=1725531998~exp=1725535598~hmac=ad88d8404a22ca877c58752beebe881848217f3a74389e8696a9c8924870fc98&w=900 "City 3")

   6.

   <details>
<summary>План проекта</summary>
<details>
<summary>Необходимые условия</summary>
<details>
<summary>Назначить дату стартового совещания</summary>

 - Определить участников
 - Подготовить повестку дня
</details>
<details>
<summary>Определить проблемы</summary>

- Провести анализ текущей ситуации
- Выявить основные проблемы и риски
</details>
<details>
<summary>Договориться о целях</summary>

- Определить краткосрочные цели
- Определить долгосрочные цели
</details>
</details>

<details>
<summary>Начальный этап</summary>
<details>
<summary>Обсудить требования</summary>

 - Сбор требований от заинтересованных сторон
 - Приоритизация требований
</details>
<details>
<summary>Внести необходимые правки</summary>

- Рассмотреть отзывы команды
- Обновить требования на основе обсуждений
</details>
<details>
<summary>Сформировать окончательный план ресурсов</summary>

- Определить необходимые ресурсы (человеческие, технические)
- Составить бюджет проекта
</details>

<details>
<summary>Определить зону ответственности каждого члена команды</summary>

- Назначить роли и обязанности
</details>
</details>

<details>
<summary>Разработка</summary>
<details>
<summary>Разработка БД</summary>

 - Проектирование структуры базы данных
 - Реализация и тестирование БД
</details>
<details>
<summary>Разработка API</summary>

- Определение спецификаций API
- Реализация и тестирование API
</details>
<details>
<summary>Разработка пользовательского интерфейса</summary>

- Создание прототипов интерфейса
- Реализация интерфейса и интеграция с API
</details>
</details>

<details>
<summary>Тестирование</summary>
<details>
<summary>Разработка стратегии тестирования</summary>

 - Определение типов тестирования
 - Создание плана тестирования
</details>
<details>
<summary>Проведение тестирования</summary>

- Проведение модульного тестирования
- Проведение интеграционного тестирования
- Проведение системного тестирования
</details>
<details>
<summary>Отчет по итогам тестирования</summary>

- Составление отчета о найденных дефектах
- Подготовка рекомендаций по исправлению
</details>
</details>

<details>
<summary>Предоставление готового продукта заказчику</summary>
<details>
<summary>Подготовка документации</summary>

 - Пользовательская документация
 - Техническая документация
</details>
<details>
<summary>Внесение финальных правок на основе обратной связи</summary>

- Проведение демонстрации продукта для заказчика
- Получение обратной связи от заказчика
- Внесение соответствующих правок
</details>
</details>

<details>
<summary>Завершение проекта</summary>

- Проведение итогового совещания с командой
- Оценка результатов проекта
- Архивирование документации и материалов проекта
</details>

</details>

   7. Java:

   ```java

   public class SwapNumbers {

    public static void main(String[] args) {

        float first = 1.20f, second = 2.45f;

        System.out.println("--Before swap--");
        System.out.println("First number = " + first);
        System.out.println("Second number = " + second);

        // Value of first is assigned to temporary
        float temporary = first;

        // Value of second is assigned to first
        first = second;

        // Value of temporary (which contains the initial value of first) is assigned to second
        second = temporary;

        System.out.println("--After swap--");
        System.out.println("First number = " + first);
        System.out.println("Second number = " + second);
    }
   }

   ```

   C++:


   ```c++

    #include <iostream>
    using namespace std;

    int main() {    s
        int number;

        cout << "Enter an integer: ";
        cin >> number;

        cout << "You entered " << number;    
        return 0;
    }

   ```

   8.
   
   > Когда ты молод и смотришь телевизор, то думаешь, что телекомпании сговорились и хотят сделать людей тупыми. Но потом ты взрослеешь и приходит понимание — люди сами этого хотят. И это гораздо более пугающая мысль. Заговор — это не страшно, ты можешь пристрелить ублюдков, начать революцию. Но нет никакого заговора, телекомпании просто удовлетворяют спрос. К сожалению, это правда.

   9. См. выше + [Оглавление](#оглавление)
   
   10. :pencil: :bangbang:
   
   Так как Markdown поддерживает оповещения, для обозначения важной информации можно воспользоваться следующим:
   
   > [!IMPORTANT]
   > Важная информация!
   
   ## Заключение

   **Вывод:** в ходе проделанной работы было успешно выполнено общее задание. Данное задание позволило приобрести базовые навыки работы с языком Markdown, которые впоследствие будут применяться в написании READMI.md файла к дипломной работе. Сложностей при выполнении общей части задания не возникло. Работа считается завершенной.

   ---

[^1:] [Источник: freepic](https://www.freepik.com/)