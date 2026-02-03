
<div align="right">
  <details>
    <summary >🌐 Language</summary>
    <div>
      <div align="center">
        <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=en">English</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=zh-CN">简体中文</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=zh-TW">繁體中文</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=ja">日本語</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=ko">한국어</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=hi">हिन्दी</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=th">ไทย</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=fr">Français</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=de">Deutsch</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=es">Español</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=it">Italiano</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=ru">Русский</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=pt">Português</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=nl">Nederlands</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=pl">Polski</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=ar">العربية</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=fa">فارسی</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=tr">Türkçe</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=vi">Tiếng Việt</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=id">Bahasa Indonesia</a>
        | <a href="https://openaitx.github.io/view.html?user=fivemru&project=export-vk-playlist-to-file&lang=as">অসমীয়া</
      </div>
    </div>
  </details>
</div>

# Как перенести музыку из Вконтакте (ВК) в Яндекс Музыку

Экспорт своего плейлиста из ВК в текстовый файл и импорт в яндекс музыку.
Скрипт может сработать и не в своих плейлистах.

```quote
Страница импорта в яндекс музыке поменялась на https://music.yandex.ru/newimport
Теперь там вроде можно импортировать через ВК сразу, не проверял.
```

## Экспорт музыки ВК в текстовый файл

Открыть в ВК страницу со своей музыкой, нажать `F12`.

Скопировать скрипт со страницы
https://raw.githubusercontent.com/fivemru/export-vk-playlist-to-file/main/chrome-snippet.js
вставить его в консоль на странице ВК, и нажать `Enter`.

*Скрипт проскроллит страницу до конца, чтобы прогрузился весь список и сохранит в файл `vk-playlist.txt`*

__Скрины:__
![image](https://user-images.githubusercontent.com/30273470/131132113-f00dc4d0-4bf1-4e96-be4f-5c22ef640695.png)

Список песен в файле

![image](https://user-images.githubusercontent.com/30273470/131132412-d9f8453f-babd-4d9d-b439-84a9df2ec586.png)

Готово.
