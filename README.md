# BuildMart (HTML / CSS / JS)

Статический магазин стройматериалов по примеру репозитория **[Egnatius-ww/WEB](https://github.com/Egnatius-ww/WEB)** и странице **[каталога на GitHub Pages](https://egnatius-ww.github.io/WEB/html/catalog.html)**. React не используется.

## Структура

- `index.html` — переход на каталог
- `html/catalog.html` — каталог товаров, фильтры, сортировка
- `html/card.html` — карточка товара (`?id=…`)
- `html/cart.html` — корзина
- `styles/` — стили (`main`, `header`, `catalog`, `footer`, toast)
- `scripts/` — логика (корзина в `localStorage`, каталог, шапка, подвал, тосты)
- `assets/icons.svg` — SVG-спрайт иконок

## Как открыть

Из папки **BuildMart** запустите статический сервер:

```bash
cd BuildMart
npx --yes serve .
```

Откройте в браузере адрес сервера: **/** или **/html/catalog.html**.

## Лицензия исходного репозитория

Код взят из публичного репозитория автора примера; при публикации проверьте лицензию в [репозитории WEB](https://github.com/Egnatius-ww/WEB).
