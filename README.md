# VYZYA — vyzya.com

Сайтът на VYZYA, марката зад WeatherPulse и бъдещите проекти.

Статичен сайт без build стъпка, публикуван с GitHub Pages.

## Файлове

- `index.html` — началната страница (стиловете са вътре)
- `assets/` — лого (SVG и PNG), иконки, картина за споделяне в социалните мрежи
- `CNAME` — домейнът за GitHub Pages (`vyzya.com`)
- `robots.txt`, `sitemap.xml` — за търсачките

## Публикуване

Settings → Pages → Deploy from a branch → `main` / `(root)`.

DNS за `vyzya.com`:

| Тип   | Име | Стойност                  |
|-------|-----|---------------------------|
| A     | @   | 185.199.108.153           |
| A     | @   | 185.199.109.153           |
| A     | @   | 185.199.110.153           |
| A     | @   | 185.199.111.153           |
| CNAME | www | vladdimitrov.github.io    |

`vyzya.eu` — постоянно пренасочване (301) към `https://vyzya.com` при регистратора.
