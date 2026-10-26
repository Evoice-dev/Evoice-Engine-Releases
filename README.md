<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/logo-white.png">
  <img src="images/logo-dark.png" alt="Evoice" width="340">
</picture>

<h3>Движок для создания 2D игр — от идеи до готовой игры для браузера, Windows и Android</h3>

[![Скачать для Windows](https://img.shields.io/badge/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C-Windows%2064--bit-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/Evoice-dev/Evoice-Engine-Releases/releases/latest)

![version](https://img.shields.io/github/v/release/Evoice-dev/Evoice-Engine-Releases?label=version&color=4c6ef5)
![downloads](https://img.shields.io/github/downloads/Evoice-dev/Evoice-Engine-Releases/total?label=downloads&color=20c997)
![builds](https://img.shields.io/badge/builds-HTML5%20%7C%20Windows%20%7C%20Android-e8590c)

[Возможности](#возможности) · [Скриншоты](#скриншоты) · [Установка](#установка) · [Лицензия](#лицензия)

<br>

<img src="images/editor.jpg" alt="Редактор Evoice Engine" width="100%">

</div>

<br>

## О проекте

**Evoice Engine** — визуальный редактор и движок для 2D игр в духе Unity, но проще. Собирайте сцену из готовых виджетов, программируйте блоками, как в Scratch, или пишите код на JavaScript и Python, проверяйте игру на эмуляторе телефона и собирайте её одной кнопкой для Яндекс Игр, Windows или Android.

> Здесь публикуются установщики и описания версий. Исходный код движка закрыт.

## Возможности

<table>
<tr>
<td width="50%" valign="top">

### 🎬 Редактор в стиле Unity
Сцена, дерево объектов, инспектор, ассеты, отмена и повтор. Якоря и адаптив под любые экраны, предпросмотр разных разрешений. Перетаскивание файлов прямо из проводника.

</td>
<td width="50%" valign="top">

### 🧩 Три способа программировать
Блоки как в Scratch, JavaScript и Python с подсказками в редакторе. Глобальные переменные и доступ к переменным других скриптов. Списки, типы данных, функции.

</td>
</tr>
<tr>
<td valign="top">

### 📱 Эмулятор телефона
Популярные модели, портретная и альбомная ориентация, наклон (акселерометр), встряска, вибрация и экранный джойстик — всё проверяется без телефона.

</td>
<td valign="top">

### ⚙️ Физика и триггеры
Rigidbody 2D и Collider 2D на Box2D, упругость и трение, триггер-зоны с событиями «вошёл» и «вышел».

</td>
</tr>
<tr>
<td valign="top">

### ✨ Частицы и освещение
Огонь, дым, искры, взрыв, магия, снег и дождь. 2D-освещение: точечный свет, прожекторы, общий свет, тени и мерцание.

</td>
<td valign="top">

### 🎞️ Анимации
Таймлайн с ключевыми кадрами и плавностью переходов. Режим записи: двигайте объект — ключи создаются сами. Анимация градиентов и цвета.

</td>
</tr>
<tr>
<td valign="top">

### 🔊 Звук
Музыка и эффекты, пространственный звук (громкость и стерео по расстоянию до игрока), эхо, реверберация, фильтры и готовые наборы: пещера, под водой, рация.

</td>
<td valign="top">

### 📦 Сборка одной кнопкой
HTML5 и Яндекс Игры, Windows `.exe`, Android `.apk` без Android Studio — нужные компоненты ставятся прямо из движка. Система сохранений с облаком Яндекс Игр.

</td>
</tr>
</table>

Полный список возможностей каждой версии — на странице **[Releases](https://github.com/Evoice-dev/Evoice-Engine-Releases/releases)**.

## Скриншоты

<table>
<tr>
<td width="50%"><img src="images/lighting.jpg" alt="Освещение и частицы на сцене"><p align="center"><sub>Освещение, тени и частицы прямо в редакторе</sub></p></td>
<td width="50%"><img src="images/game.jpg" alt="Запущенная игра с джойстиком"><p align="center"><sub>Игра: свет, огонь и экранный джойстик</sub></p></td>
</tr>
<tr>
<td><img src="images/blocks.jpg" alt="Блочное программирование"><p align="center"><sub>Блоки в стиле Scratch</sub></p></td>
<td align="center"><img src="images/splash.jpg" alt="Заставка" width="70%"><p align="center"><sub>Заставка при запуске</sub></p></td>
</tr>
</table>

## Установка

1. Откройте **[последний релиз](https://github.com/Evoice-dev/Evoice-Engine-Releases/releases/latest)** и скачайте в разделе **Assets** файл **`Evoice-Engine-Setup-<версия>.exe`**.
2. Запустите установщик и следуйте шагам — ярлык появится на рабочем столе и в меню «Пуск».
3. Если Windows покажет окно «Система Windows защитила ваш компьютер», нажмите **«Подробнее» → «Выполнить в любом случае»**: установщик пока не подписан сертификатом.

| Системные требования | |
|---|---|
| Система | Windows 10 или 11, 64-бит |
| Место на диске | около 500 МБ |
| Сборка игр для Android | интернет при первой установке компонентов (около 300 МБ, ставятся из движка) |

После запуска откроется список проектов — нажмите «Новый проект» и выберите шаблон «Платформер», «Кликер» или «Пустой проект». Справка по API и блокам открывается в движке клавишей <kbd>F1</kbd>, руководство пользователя лежит в папке программы.

## Лицензия

**Evoice Engine** — проприетарное программное обеспечение. © 2026 Evoice Studio. Все права защищены.

Движок распространяется бесплатно на условиях **[лицензионного соглашения](EULA.txt)**. Игры, созданные в Evoice Engine, принадлежат их авторам — их можно публиковать и продавать.

Движок использует библиотеки с открытым исходным кодом (Electron, Blockly, Monaco Editor, planck.js, Brython и другие); их лицензии лежат в файле `THIRD_PARTY_LICENSES.txt` в папке программы.

<div align="center">
<br>
<sub>Сделано в <b>Evoice Studio</b></sub>
</div>
