НАСТРОЙКА ОКРУЖЕНИЯ


- на скрине "RESULT.jpg" показано как отрабатывает браузер по хосту по умолчанию и по виртуальному хосту test.local
- подтверждением того, что php отрабатывает является корректная выдача страниц
- также на скрине вид символических ссылок в папке активных конфигугаций nginx'a

- в хранилище index.php, в котором представлен исходный код на php.  
- также в хранилище файл hosts, в котором видно проброс в локальную сеть адреса test.local (там ещё лежат пробросы от виртуалки, т.к. линкус на ней вращается).

- приложены файлы конфигурации nginx'a (для локалхоста и тест.локал, содержимое - самое минимальное для работы).

понимаю, что можно сделать все виртуальные хосты в одной default-конфигурации, просто добавляя разделы, но пока не понимаю какой вариант лучше: править общий конфиг, или конфиги каждого хоста (с учётом, что требуется перезапуск nginx'а).
