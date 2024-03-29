##Проста обробка текстових даних засобами оболонки Unix-подібних ОС інтерпретора команд ОС. 
### 1 Навігація по файловій системі через засоби оболонки Git Bash інтерпретатору командного рядку Bash

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/1.png)
Рис. 1 – Фрагмент екрану з рішення завдання 2.2.1 "Отримати перелік файлів поточного каталогу з урахуванням видимості прихованих файлів."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/2.png)
Рис. 2 – Фрагмент екрану з рішення завдання 2.2.2 "Перейти до прихованого каталогу .git, використовуючи команду pushd з метою
швидкого повернення до попереднього каталогу у майбутньому."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/3.png)
Рис. 3 – Фрагмент екрану з рішення завдання 2.2.3 "Переглянути вміст файлу config, використовуючи редактор nano."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/4.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.2.4 "Отримати перелік файлів поточного каталогу з урахуванням наступних умов:
-відображення списку файлів у псевдо табличному форматі;
-впорядкування порядку слідування файлів за убуванням їх розміру."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/5.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.2.5 "Повернутися до каталогу, використовуючи команду швидкого повернення."

### 2 Налаштування псевдонімів команд оболонки Bash
![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/6.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.3.1 "Виконати команду зі створення псевдоніму виклику команди, пов’язаною з Bash командою у відповідності з таблицею 4. Перевірити роботу псевдоніму команди."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/7.png)
Рис. 5 – Фрагмент екрану з рішення завдання 2.3.3 "Перейти до домашнього каталогу вашого користувача. Використовуючи текстовий редактор розпочати редагування файлу .bash_profile та додати у файл два рядки зі створеними раніше псевдонімами виклику команд."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/8.png)
Рис. 6 – Фрагмент екрану з рішення завдання 2.3.5 "Повторно запустити GitBash-оболонку та перевірити роботу одного зі створених псевдонімів команд, щоб підтвердити їх автоматичну реєстрацію через файл .bash_profile"

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/236.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.3.6 "Скопіювати файл .bash_profile до каталогу «Laboratory-work-3» Git-репозиторію."

### 3 Робота з файлами через перенаправлення вхідних/вихідних потоків
![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/241.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.4.1 "Створити файл з назвою як транслітерація вашого прізвища з прикінцевою цифрою 1, наприклад blazhko_1, використовуючи команду cat з перенаправленням stdin-потоку на stdout-потік так, що файл містив один рядок з вашими прізвищем та ім’ям." ; 2.4.2 "Додати до створеного файлу через перенаправлення stdout-потоку ще один рядок з назвою вашої групи."

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/243.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.4.3 "Створити файл з назвою як транслітерація вашого імені з прикінцевою цифрою 2, наприклад blazhko_2, який містить два рядки, створені через перенаправлення stdout-потоку двох наступних команд:
-команда визначення назви поточного каталогу, в якому ви знаходитеся, формує перший рядок;
- команда визначення імені поточного користувача ОС, формує другий рядок;"

![image](https://github.com/khachatryangrigor/WebAR-Ronalds-Telegraph/blob/Laboratory-work-3/244.png)
Рис. 4 – Фрагмент екрану з рішення завдання 2.4.4 Обєднати два раніше створені файли в один файл командою cat зі створенням нового файлу, назва якого – транслітерація вашого прізвища та імені із суфіксом-розширенням .cat.txt; 2.4.5 Повторити об`єднання файлів, але вже командою paste зі створенням нового файлу, де назва файлу – транслітерація вашого прізвища та імені із суфіксом-розширенням .paste.txt.

### 4 Проста обробка результатів виконання команд
