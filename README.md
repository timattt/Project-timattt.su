# Проект timattt.su
На этом сайте будет размещаться всякие мои полезные проекты.
# Cognitia
## Описание
Это удобная утилита для постановки и выполнения задач по программированию (хотя, в сущности можно и любой курс запихнуть в прогу).   
Итак, у нас есть курс по программированию на С. Мы оформляем его в формате графа (ациклического ориентированного графа, если быть точным).
Теперь каждая его вершина - задача, которую нужно решить или полезная утилита, которую нужно изучить. Решение задачи открывает доступ к другим задачам.
Также к каждой задаче или утилите прилагается небольшой теорминимум, который можно быстро просмотреть.
И так пока курс не закончится, очень удобно и наглядно.
## Установка
### Linux
* Установите java командой "sudo apt install default-jre"
* Установите graphviz командой "sudo apt install graphviz"
* Скачайте файл установки [отсюда](https://github.com/timattt/Project-timattt.su/raw/master/Cognitia/installer/Linux/installCognitiaLinux.sh)
* Запустите консоль в директории скачанного файла
* Используйте команду "sudo ./файл installCognitiaLinux.sh"
### Windows
* Установите java [отсюда](https://www.java.com/ru/)
* Установите graphviz вот [отсюда](https://graphviz.org/download/), во время установки поставьте галочку на изменение переменной среды PATH.
* Скачайте и запустите установщик Cognitia [отсюда](https://github.com/timattt/Project-timattt.su/tree/master/Cognitia/installer/Win64).
## Руководство пользователя
В утилите есть следующие команды:    
* see - строит граф текущего прогресса. Есть дополнительные опции (вот так их можно использовать "see --dh --mc"):   
  * dh - draw hidden, рисует вообще все вершины, но те, которые еще недоступны будут серыми и со знаком вопрос.
  * mc - more colors, добавляет больше цветов разным типам вершин.   
* unlock [vertex id] - открывает вершину с заданным номером (номер указан в начале названия вершины, можно увидеть с помощью команды see).   
* man [vertex id] - отображает в браузере теорминимум к вершине с заданным номером.   
