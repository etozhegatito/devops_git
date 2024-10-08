# DevOps Test Assignment

## Приветствие

Привет! Меня зовут Санжар, я студент 4 курса SDU University по специальности **Информационные Системы**. В этом репозитории вы найдете решение тестового задания по DevOps, которое включает задачи по Linux, Git, программированию на Bash и логическому мышлению.

## Описание проекта

В рамках тестового задания были выполнены следующие шаги:

1. **Основы Linux**:
   - Создание директории `devops_sobes` в домашнем каталоге.
   - Создание пустого файла `readme.txt` в этой директории.
   - Показ текущего пути в терминале.

2. **Основы Git**:
   - Создание нового локального репозитория.
   - Создание файла `test.txt` с текстом "Hello DevOps".
   - Коммит изменений с сообщением "Initial commit".
   - Просмотр истории коммитов.

3. **Программирование (Bash скрипт)**:
   - Написан скрипт на Bash, который выводит числа от 1 до 10.

4. **Логическое мышление**:
   - Решение задачи на определение, какой выключатель управляет какой лампочкой.

## Как я сделал это

### 1. Основы Linux

- **Создание директории**:
  ```bash
  mkdir ~/devops_sobes

Создание пустого файла readme.txt:

bash

touch ~/devops_sobes/readme.txt

Показ текущего пути:

bash

    pwd

2. Основы Git

    Создание локального репозитория:

    bash

mkdir ~/devops_sobes_repo
cd ~/devops_sobes_repo
git init

Создание файла test.txt с текстом "Hello DevOps":

bash

echo "Hello DevOps" > test.txt

Коммит изменений:

bash

git add test.txt
git commit -m "Initial commit"

Просмотр истории коммитов:

bash

    git log

3. Программирование (Bash скрипт)

    Создание Bash-скрипта numbers.sh, который выводит числа от 1 до 10:

    bash

echo -e '#!/bin/bash\nfor i in {1..10}; do\n    echo $i\ndone' > numbers.sh
chmod +x numbers.sh

Запуск скрипта:

bash

    ./numbers.sh

4. Решение задачи на логическое мышление + ответы на теор. вопросы 

1. Что такое IP-адрес и для чего он используется?

    IP-адрес — это уникальный номер, который присваивается каждому устройству в сети (например, компьютеру или смартфону). Он используется для того, чтобы устройства могли      находить и общаться друг с другом через интернет или другую сеть.

2. Основные отличия между протоколами TCP и UDP:

    TCP: Надежный протокол. Он гарантирует, что данные будут доставлены правильно и в том порядке, в котором были отправлены. Используется для таких вещей, как просмотр веб-страниц или отправка электронной почты.
    UDP: Быстрый, но ненадежный протокол. Он не проверяет, все ли данные дошли. Используется для стриминга видео или онлайн-игр, где важнее скорость, а не точность передачи данных.

3. Описание решения задачи с лампочками:

    1. Включить первый выключатель на несколько минут.
    2. Выключить его, включить второй выключатель и идти в комнату.
    3. Горящая лампочка управляется вторым выключателем.
    4. Тёплая лампочка, которая не горит, управляется первым выключателем.
    5. Холодная лампочка управляется третьим выключателем.

Скриншоты

    Настройка git и создание папок: Создание файлов
![image alt](https://github.com/etozhegatito/devops_git/blob/651d5b8447e1cded55fb5bdc8b8fd76fb4071275/1.png)

    Создание файла и вывод текущего пути: Создание readme.txt

![image alt](https://github.com/etozhegatito/devops_git/blob/651d5b8447e1cded55fb5bdc8b8fd76fb4071275/2.png)

    Создание файла с Bash скриптом и вывод чисел: Bash-скрипт

![image alt](https://github.com/etozhegatito/devops_git/blob/651d5b8447e1cded55fb5bdc8b8fd76fb4071275/3.png)


MY CV

![image alt](https://github.com/etozhegatito/devops_git/blob/a86701a5546f89197e21f6ab136b7db83b804740/My%20Resume-1-1.png)


Спасибо за внимание! Если у вас есть вопросы или предложения, буду рад обсудить их. 😊




