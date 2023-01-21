# Домашнее задание к лекции «История и работа с ветками»

## Задача №2 - Слияние изменений

1. Склонировать [Git-репозиторий](https://github.com/netology-code/git-homeworks-neuro-merge/tree/master);
1. Слить ветку **origin/feature/earlyorder** с веткой **main** 
1. Разрешить появившийся при слиянии конфликт;
1. Отправить изменения ветки `main` в удалённый новый репозиторий `target`.  
В качестве результата пришлите ссылку на ваш репозиторий на GitHub.

**Результат выполнения задачи:**  
[ссылка на текущий репозиторий на GitHub](https://github.com/Ekaterina-Isabel/git-homeworks-neuro-merge)  
[список коммитов с merge](https://github.com/Ekaterina-Isabel/git-homeworks-neuro-merge/commits/master)


## Задача №3 - Работа с историей и переключение между коммитами

Выяснилось, что перестала работать достаточно важная функция. Известно лишь, что всё работало в коммите `c2e06a`, а когда перестало работать - неизвестно. Нужно найти в каком из коммитов функция сломалась и кто её сломал.  
1. Необходимый [Git-репозиторий](https://github.com/netology-code/git-homeworks-neuro-broken);
1. Переключиться на коммит `c2e06a`, удостовериться что функция работает*;
1. Переключиться на последний коммит;
1. Используя команды переключения между коммитами, определить в каком коммите и кем была внесена ошибка.

**Примечание**:\* чтобы проверить, что функция работает, нужно открыть в браузере файл `index.html` (два раза кликните на этом файле в файловом менеджере), ввести в поле ввода подписки адрес электронной почты и нажать кнопку. В коммите `c2e06a` форма работает, после отправки формы появляется окошко с текстом.

Окошко с текстом будет выглядеть примерно вот так (если у вас тёмная тема оформления браузера):
![image](https://user-images.githubusercontent.com/79922872/213866672-adba58c7-e312-42d9-9c0e-cab15af0f8ed.png)

**В качестве результата пришлите Имя автора и идентификатор первого коммита, в котором функция перестала работать.**

## Результат выполнения задачи:  
Author: Oleg oleg@localhost  
b55791692d102a18cd62e7d92deb915119f2c8b2
