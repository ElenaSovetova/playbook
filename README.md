# playbook



Плэйбук устанавливает на виртуальные машины 
* Clickhouse
* Lighthouse
(lighthouse будет установлен в /home/lighthouse
На ВМ вместе с lighthouse так же будет запущен веб-сервер nginx, который  будет скачиваться с epel-репозитория  при запуске плейбука.)
* Vector
(версия:0.21.0
 Файл установки Vector- vector_rpm )
 
------------
В плэйбуке прописаны тэги
* tags: nginx
* tags: clickhouse
* tags: vector
* tags: lighthouse

