# Библиотека по машинному обучению
## Описание
Данная библиотека преднзначена для облегчения использования технологий машинного обучения
на языке программирования Java 11 версии.
В данном проекте приведен пример работы с библиотекой - в папке Example. Но предворительно, для запуска надо подключить билиотеку. 
Как это сделать описано ниже.
### Функционал:
- Многослойный перцептрон - модель нейронной сетию
- Обучение многослойного перцептрона на методе обратного распространения ошибки.
## Установка
### Для использования
Для использования описанного выше функцонала надо скачать последнюю версию библиотеки ML-1.0.jar.
В своём проекте надо перейти в раздел "File->Project Structure->Libraries", после чего добавить скачанную библиотеку.
В описании библиотеки должно высветиться два пункта: "Classes", "Sources". 
Если "Sources" не появился, то в этом описании надо нажать на дбавление и выбрать тот же файл.
Это надо для того, чтобы было описание.
### Для изменения
Для сборки проекта в один .jar файл надо в терминале, относительно корневой папки проекта, прописать:
```
mvn install
```
Если в собранном пректе не нужен исходный код, то для этого надо в файле pom.xml убрать добавление исходников в тэге <build>.
