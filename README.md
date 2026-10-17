# Русификатор Arknights

Здравствуйте, мы команда проекта по русификации Arknights. Здесь мы будем делиться новостями, обновлениями и прогрессом перевода.

---

## Чем мы являемся и что предлагаем

Перевод будет предоставляться в двух версиях:

- **Только ручной перевод**: здесь будут представлены переводы [Бухой чайной Совы](https://vk.ru/tea_owl_mari_hoshi), [Saloejk'и](https://vk.ru/saloblog), [Gethris'а](https://www.youtube.com/@Gethris) и иных переводчиков из сообщества.
- **Ручной перевод + ИИ**: всё то же самое, что и выше, но весь непокрытый текст будет переведён с помощью ИИ. Впрочем, спешим заверить, что как минимум проверку глоссарием и базовой вычиткой человеком оно будет проходить, кормить слопом вас никто не будет. По мере жизни проекта ручные переводы, естественно, будут заменять собой прошлые машинные переводы.
- **Приятный русский шрифт**.

---

## На каком мы этапе

- Ручные переводы пока в процессе переноса. Часть сюжетов, личных дел и прочего уже в игре, их количество постоянно растёт. Доступ к этой версии появится при достижении ими определённой критической массы.
- Машинный перевод на данный момент покрывает практически весь текст в игре, но так как он не являлся и не будет являться приоритетным, то сейчас его качество далеко от идеала. А если говорить честно, то даже проверок особо пока не проходил. Вариант для самых нетерпеливых. Однако напомню про слова выше — улучшаться он будет.

Для установки русификатора прочитайте наш [гайд по установке](https://t.me/ru_arknights/12).

Подписывайтесь на [канал/группу](https://t.me/ru_arknights), чтобы быть в курсе всех новостей обновлений!

---

## Как работает наш перевод

Перевод осуществляется двумя способами:

- Тексты сюжетов заменяются локально (мы прямо в файлах заменяем английский текст на русский). Файлы эти незашифрованные, поэтому подобные манипуляции со стороны игры незаметны.
- Весь текст, что хранится в зашифрованных файлах, переводится с помощью [BepInEx](https://github.com/BepInEx/BepInEx) и плагина [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator). Сделано это было по той причине, что мы считаем не особо разумным и правильным шагом полностью отключать у игры криптографию. Процесс замены текста происходит во время выполнения игрой своего кода, взаимодействия с файлами игры нет. По той причине, что клиент Yostar, в отличие от китайских клиентов, не имеет в себе античита, подобные манипуляции со стороны игры также незаметны.

> **Впрочем, не стройте иллюзий**: описанное выше никак не отменяет того факта, что всё это прямое нарушение пользовательского соглашения. И вам никто не гарантирует 100% безопасность. Просто с нашей стороны риски оцениваются крайне минимально, конечно, при условии, что вы не будете «светить» русским текстом в игре на официальных площадках, и при условии, что Yostar не решат резко отслеживать и банить игроков за подобные манипуляции с игрой.

---

[ArknightsRU | Русификатор](https://t.me/ru_arknights)

## Скриншоты продукта

<div align="center">
  <img width="1280" height="720" alt="Все оперативники и меню" src="https://github.com/user-attachments/assets/8d5fa3e0-094d-4ebf-bfb6-4f3bc0619f89" />
  <br>
  <i>Все оперативники и меню</i>
</div>

---

<div align="center">
  <img width="1280" height="720" alt="Сюжетные диалоги" src="https://github.com/user-attachments/assets/efe46ccb-97f1-4e2e-ab76-d2958ee33620" />
  <br>
  <i>Сюжетные диалоги</i>
</div>

---

<div align="center">
  <img width="1150" height="645" alt="Собственный лаунчер" src="https://github.com/user-attachments/assets/26c8e58f-094a-4182-9e40-010de7fba00d" />
  <br>
  <i>Собственный лаунчер</i>
</div>

<br>

<details>
<summary><b>🇬🇧 Click here to read in English / Нажмите, чтобы прочитать на английском</b></summary>

<br>

# Arknights Localization

Hello, we are the team behind the Arknights Russian localization project. Here we will share news, updates, and translation progress.

---

## What we are and what we offer

The translation will be provided in two versions:

- **Manual translation only**: this will feature translations by [Bukhaya Chainaya Sova](https://vk.ru/tea_owl_mari_hoshi), [Saloejka](https://vk.ru/saloblog), [Gethris](https://www.youtube.com/@Gethris), and other community translators.
- **Manual translation + AI**: same as above, but any uncovered text will be translated using AI. However, we assure you that it will undergo at least a glossary check and basic human proofreading; we won't feed you slop. As the project progresses, manual translations will naturally replace previous machine translations.
- **A pleasant Russian font.**

---

## Our Current Stage

- Manual translations are currently in the process of being ported. Some stories, operator files, and other texts are already in the game, and their number is constantly growing. Access to this version will be granted upon reaching a certain critical mass.
- Machine translation currently covers almost all text in the game, but since it was not and will not be a priority, its quality is far from ideal right now. To be honest, it hasn't even undergone much checking yet. It's a version for the most impatient. However, as mentioned above, it will improve.

To install the localization, please read our [installation guide](https://t.me/ru_arknights/12).

Subscribe to our [channel/group](https://t.me/ru_arknights) to stay updated on all news and updates!

---

## How our translation works

The translation is done in two ways:

- Story texts are replaced locally (we directly replace the English text with Russian in the files). These files are unencrypted, so such manipulations are invisible to the game.
- All text stored in encrypted files is translated using [BepInEx](https://github.com/BepInEx/BepInEx) and the [XUnity.AutoTranslator](https://github.com/bbepis/XUnity.AutoTranslator) plugin. This was done because we consider it unwise and improper to completely disable the game's cryptography. The text replacement process occurs during the game's code execution, with no interaction with the game files. Since the Yostar client, unlike the Chinese clients, does not have an anti-cheat, such manipulations are also invisible to the game.

> **However, do not be under any illusions**: the above does not negate the fact that this is a direct violation of the Terms of Service. And no one guarantees you 100% safety. We simply assess the risks as extremely minimal, provided, of course, that you do not 'flaunt' the Russian text in the game on official platforms, and provided that Yostar does not suddenly decide to track and ban players for such manipulations with the game.

---

[ArknightsRU | Localization](https://t.me/ru_arknights)

## Product Screenshots

<div align="center">
  <img width="1280" height="720" alt="All Operators and Menu" src="https://github.com/user-attachments/assets/8d5fa3e0-094d-4ebf-bfb6-4f3bc0619f89" />
  <br>
  <i>All Operators and Menu</i>
</div>

---

<div align="center">
  <img width="1280" height="720" alt="Story Dialogues" src="https://github.com/user-attachments/assets/efe46ccb-97f1-4e2e-ab76-d2958ee33620" />
  <br>
  <i>Story Dialogues</i>
</div>

---

<div align="center">
  <img width="1150" height="645" alt="Custom Launcher" src="https://github.com/user-attachments/assets/26c8e58f-094a-4182-9e40-010de7fba00d" />
  <br>
  <i>Custom Launcher</i>
</div>

</details>
