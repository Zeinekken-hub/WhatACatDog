Краткое описание:
Фото должно быть формата .jpg. Сперва определяется вероятность того, собака это или кот, затем вызывается модель распознавания породы
кота или собаки.
Все фотографии сжимаются, размер во время обработки становится 64*64 пикселя. Точность распознавания вида животного (кот или собака) = 97%,
точность распознавания породы животного = 60%.
Модели имеют формат .h5 (бинарные файлы, в них НЕ записан код, лучше их не открывать). 
Основной файл, который следует запускать - predict.py. В нем не создаются модели, а уже используются ранее созданные. Пока что на выходе
получаем фотку, на ней вероятности. Еще эти значения дополнительно выводятся ПОКА ЧТО в консоль. (TODO: перенаправить потоки вывода для веб, в телегу).


