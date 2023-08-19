# Видеоплеер

Вёрстка видеоплеера, за основу взята java-script библиотека [video-player-jslib](https://github.com/devmanorg/video-player-jslib).

# Необходимые зависимости

Первым делом, скачайте код:

```shell
git clone https://github.com/pas-zhukov/video-player.git
```

Репозиторий уже содержит файл java-script библиотеки плеера.

CSS-библиотеки подключены в `index.html` по ссылкам из интернета.

# Запуск на локальной машине

Вы можете открыть `index.html` в любом браузере.

Если Вы хотите внести изменения в код, будет удобно использовать консольную утилиту [livereload](https://livereload.readthedocs.io/en/stable/), т.к. она позовлит отображать изменения в реальном времени. Установите её командой:

```shell
pip install livereload
```
или, если у вас нет pip:

```shell
easy_install livereload
```

Запустите утилиту командой:

```shell
livereload -t <путь к файлу `index.html`>
```
