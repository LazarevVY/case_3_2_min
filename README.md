# case_3_2_minimum

Минимально необходимое задание:

Ознакомиться с материалами раздела 3.2
Ознакомиться со структурой данных о публикации, возвращаемой сервером в ответ на запрос https://jsonplaceholder.typicode.com/posts/1
Создать класс Post, повторяющий структуру ответа сервера. Реализовать в нём конструктор и метод конвертации из JSON (см. класс Album в примере)
Реализовать функцию загрузки и конвертации данных в объект (см. fetchAlbum() в примере)
Создать виджет с состоянием. В методе initState вызывать загрузку данных. В методе build реализовать отображение заголовка и тела публикации с помощью FutureBuilder