# rosbag-publisher
rosbag record --publisher=PUBLISHER - record all topics published by a node

Ключ для rosbag record, позволяющий записывать информацию из тем, соответствующей заданной ноде. 
Аналог --node=NODE - record all topics subscribed to by a specific node.

Приложена целиком папка ros_comm/tools/rosbag. 
В файле rosbag_main.py ключ добавлен в парсер, также изменены файлы record.cpp, recorder.cpp и recorder.h

Сборка аналогична стандартной сборке ros, новых файлов не добавлено.
Протестировать можно с помощью turtlesim, например, действуя по аналогии с rosbag record --node=NODE
