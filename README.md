<p align="center">
  <img src="icons/icon-192.png" width="96" alt="Stroy">
</p>

<h1 align="center">Stroy — гитарный тюнер / guitar tuner</h1>

<p align="center">
  <b><a href="https://xnyokkiisreal.github.io/stroy/">▶ Открыть тюнер / Open the tuner</a></b><br>
  <sub>Создатель / Made by <b>xnyokki</b></sub>
</p>

---

## 🇷🇺 Русский

**Stroy** — бесплатный тюнер для гитары, который работает прямо в браузере. Он слушает гитару через микрофон, показывает, какую струну крутить, в какую сторону и примерно насколько повернуть колок. Главное — он умеет **альтернативные строи**: можно за минуту перестроиться из стандарта в Drop D, D Standard, Open G и другие, не зная наизусть нужные ноты.

### Возможности
- **27 строёв**: стандартные (E, Eb, D, C#, C, B, A), Drop (D, C#, C, B, A#, A, Double Drop D), открытые (Open G, D, E, A, C, Dm, DADGAD), «Все кварты», Nashville и **7-струнные**.
- **Свой строй**: собери любой строй кнопками +/− и сохрани его.
- **Подсказки**: «подтяни» или «ослабь», сколько полутонов осталось и примерно на сколько оборотов повернуть колок. Под каждой струной видно, насколько её сдвинуть от стандарта.
- **Стрелка или строб**: плавная стрелка либо строб-режим, как у профессиональных тюнеров, для точности меньше одного цента.
- **Три режима**: «Авто» сам ловит любую струну, «По порядку» ведёт от струны к струне, «Одна струна» слушает только выбранную.
- **Проверка мензуры**: сравнение 12-го лада с открытой струной и совет, в какую сторону сдвинуть седло.
- **Точный эталонный звук** каждой струны; пока он звучит, тюнер не слушает сам себя.
- **15 языков** с автоопределением: русский, украинский, английский, французский, немецкий, испанский, португальский, итальянский, польский, турецкий, китайский, японский, корейский, арабский, хинди.
- **Устанавливается как приложение** на телефон и **работает без интернета**.
- Настройки: частота A4, точность, чувствительность, выбор микрофона или аудиоинтерфейса, вибрация, экран не гаснет.

### Как пользоваться
1. Открой тюнер и нажми **«Начать»**, разреши доступ к микрофону.
2. Выбери строй, например Drop D.
3. Дёргай по одной открытой струне и следуй подсказкам, пока струна не станет зелёной.

Для электрогитары: играй через комбик или поднеси микрофон к звукоснимателям. Точнее всего — через аудиоинтерфейс (iRig, Focusrite и т.п.).

### Установка на телефон
- **Android (Chrome):** меню ⋮ → «Установить приложение».
- **iPhone (Safari):** «Поделиться» → «На экран Домой».

### Конфиденциальность
Звук обрабатывается **только на твоём устройстве**. Тюнер ничего не записывает и никуда не отправляет.

---

## 🇬🇧 English

**Stroy** is a free guitar tuner that runs right in your browser. It listens to your guitar through the microphone and tells you which string to turn, which way and roughly how far to turn the peg. Its main strength is **alternate tunings**: switch from standard to Drop D, D Standard, Open G and more in a minute, without memorising the notes.

### Features
- **27 tunings**: standard (E, Eb, D, C#, C, B, A), drop (D, C#, C, B, A#, A, Double Drop D), open (Open G, D, E, A, C, Dm, DADGAD), all fourths, Nashville and **7-string** tunings.
- **Custom tunings**: build any tuning with +/− buttons and save it.
- **Clear hints**: “tighten” or “loosen”, semitones left and roughly how many turns of the peg. Each string shows how far it moves from standard.
- **Needle or strobe**: a smooth needle or a pro-style strobe view for sub-cent accuracy.
- **Three modes**: Auto detects any string, In order guides you string by string, One string listens to the selected string only.
- **Intonation check**: compares the 12th fret with the open string and tells you which way to move the saddle.
- **Exact reference tone** for every string; the tuner pauses while it plays so it doesn't hear itself.
- **15 languages** with auto-detection: Russian, Ukrainian, English, French, German, Spanish, Portuguese, Italian, Polish, Turkish, Chinese, Japanese, Korean, Arabic, Hindi.
- **Installable as an app** on your phone and **works offline**.
- Settings: A4 reference, precision, sensitivity, microphone or audio interface choice, vibration, keep screen on.

### How to use
1. Open the tuner, press **Start** and allow microphone access.
2. Pick a tuning, for example Drop D.
3. Pluck one open string at a time and follow the hints until the string turns green.

For electric guitar: play through an amp or hold the mic close to the pickups. An audio interface (iRig, Focusrite, etc.) gives the best accuracy.

### Install on your phone
- **Android (Chrome):** menu ⋮ → “Install app”.
- **iPhone (Safari):** Share → “Add to Home Screen”.

### Privacy
Audio is processed **only on your device**. Nothing is recorded or sent anywhere.

---

## Технологии / Tech

Один HTML-файл без библиотек и без сервера / a single HTML file, no libraries, no server:
Web Audio API, распознавание высоты звука алгоритмом YIN / YIN pitch detection, PWA (manifest + service worker).

| Файл / File | Назначение / Purpose |
|---|---|
| `index.html` | приложение целиком / the whole app |
| `manifest.webmanifest` | установка на телефон / app install data |
| `sw.js` | офлайн-режим / offline support |
| `icons/` | иконки / icons |

---

<p align="center">© 2026 <b>xnyokki</b>. Все права защищены / All rights reserved.</p>
