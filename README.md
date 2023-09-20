# MNIST_work
<h3 class="markdown-body">Обучение нейронной сети распознаванию рукописного текста по картинке.</h3>


<h2 class="markdown-body">Описание</h2>
Этот репозиторий содержит код для обучения нейронной сети распознавать рукописный текст на изображениях с использованием базы данных MNIST. База данных MNIST включает в себя 70000 чёрно-белых изображений цифр от 0 до 9. Каждое изображение представлено как numpy.ndarray размером 28x28, где каждый пиксель имеет значение от 0 до 255, где более высокое значение соответствует более яркому пикселю.

<h2 class="markdown-body">Модель нейронной сети</h2>
В данной задаче была использована нейронная сеть, созданная с использованием библиотеки Keras.

<h2 class="markdown-body">Обучение модели</h2>
Модель была скомпилирована с использованием оптимизатора Adam и функции потерь categorical_crossentropy.

Для обучения модели была использована база данных MNIST, разделённая на обучающую и тестовую выборки. Модель была обучена на данных в течение нескольких эпох с размером пакета 64.

<h2 class="markdown-body">Распознавание новых изображений</h2>
Вы можете использовать обученную модель для распознавания рукописных цифр на новых изображениях. Для этого загрузите и предобработайте новое изображение и выполните предсказание с помощью модели.

<h2 class="markdown-body">Зависимости</h2>
Для запуска этого кода вам потребуется установить следующие библиотеки и их версии с помощью команды pip install -r requirements.txt

<h2 class="markdown-body">Инструкции по использованию</h2>

1. Клонируйте репозиторий на свой компьютер.

2. Запустите Jupyter Notebook или скрипты Python для выполнения анализа и обучения моделей.
