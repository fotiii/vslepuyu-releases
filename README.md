<p align="center">
  <img src="docs/banner.png" alt="Вслепую — тренажёр слепой печати" width="100%">
</p>

<h1 align="center">Вслепую</h1>

<p align="center">
  Тренажёр слепой печати для Windows с оверлеем поверх всех окон.<br>
  Русский — на обычных словах. English — на коде.
</p>

<p align="center">
  <a href="https://github.com/fotiii/vslepuyu-releases/releases/latest/download/Vslepuyu-Setup-1.0.0.exe"><img alt="Скачать для Windows" src="docs/badges/download.svg" height="56"></a>
</p>

<p align="center">
  <img alt="версия 1.0.0" src="docs/badges/version.svg">
  <img alt="Windows 10 | 11" src="docs/badges/windows.svg">
  <img alt="лицензия MIT" src="docs/badges/license.svg">
</p>

---

## Установка

1. Откройте **[последний релиз](https://github.com/fotiii/vslepuyu-releases/releases/latest)** и скачайте `Vslepuyu-Setup-x.y.z.exe`.
2. Запустите установщик, выберите папку. Права администратора не нужны.
3. Ярлык **«Вслепую»** появится на рабочем столе и в меню «Пуск».

> [!NOTE]
> Установщик пока не подписан цифровой подписью. Если Windows покажет окно «Windows защитила ваш компьютер», нажмите **Подробнее → Выполнить в любом случае**.

**Требования:** Windows 10 или 11, 64-бит, около 300 МБ на диске.

## Что внутри

<img src="docs/training-light.png" alt="Урок" width="100%">

- **Курс** — 23 урока для русской раскладки и 31 для английской: от основного ряда до предложений и строк кода.
- **Адаптивный режим** — новые буквы открываются по мере роста скорости, упор на самые слабые.
- **Код** — символы `(){}[]=><"'|&`, `camelCase` и настоящие фрагменты на JS, TS, React, Python, Bash, SQL.
- **Тест скорости, слабые места, свой текст** и подробная статистика.
- **Светлая и тёмная тема** в стиле macOS и iOS.

## Оверлей поверх всех окон

<img src="docs/overlay-ru.png" alt="Оверлей" width="100%">

Сверните приложение в оверлей и печатайте где угодно — он покажет, каким пальцем нажимать каждую клавишу, проверит Shift и посчитает скорость. Буквы текущей раскладки становятся крупными сами.

| Клавиши | Действие |
|---|---|
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>H</kbd> | показать или скрыть |
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>K</kbd> | закрепить — клики проходят насквозь |
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>J</kbd> | открыть приложение |

Размер — уголок справа внизу или <kbd>Ctrl</kbd> + колёсико.

> [!IMPORTANT]
> Оверлей получает только коды клавиш. Набранный текст не сохраняется и никуда не отправляется — приложение работает полностью офлайн.

<p align="center">
  <img src="docs/code.png" alt="Код" width="49%">
  <img src="docs/settings.png" alt="Настройки" width="49%">
</p>

## Вопросы

<details>
<summary><b>Антивирус ругается на программу</b></summary>

Оверлею нужно видеть нажатия в других окнах, поэтому он ставит стандартный системный хук клавиатуры — так работают все подобные программы. Текст при этом не записывается.
</details>

<details>
<summary><b>Оверлей не виден поверх игры</b></summary>

Полноэкранные игры перекрывают всё. Переключите игру в режим «окно без рамки».
</details>

<details>
<summary><b>Метка RU/EN не меняется</b></summary>

Выберите подписи вручную: **Настройки → Оверлей → Подписи клавиш**.
</details>

<details>
<summary><b>Как обновиться</b></summary>

Скачайте новую версию и установите поверх — прогресс сохранится.
</details>

## Нашли ошибку?

Опишите её в **[Issues](https://github.com/fotiii/vslepuyu-releases/issues/new)** — скриншот очень помогает.

---

<p align="center"><sub>История изменений — в <a href="CHANGELOG.md">CHANGELOG.md</a> · © 2026 fotiii · <a href="LICENSE">MIT</a></sub></p>
