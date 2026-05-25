# Vitgem Menopause Gummies — Бриф для дизайнера Amazon UK

Полная спецификация по 7 слотам Amazon-галереи: текст verbatim, шрифты, размеры в px, промты для генерации фонов и композиции, compliance-чеклист.

## Live-бриф

📄 **Интерактивная версия:** https://darkedid89.github.io/vitgem-menopause-gallery-brief/

## Что внутри

- `index.html` — главная интерактивная страница брифа (на русском)
- `styles.css` — премиум-стилизация (aubergine + gold + DM Sans + Playfair Italic)
- `PROMPTS_FOR_USER.md` — промты для генерации фонов сцен в ChatGPT / Nano Banana (для копи-паста)
- `STYLE_AUDIT.md` — анализ единства стиля по 6 параметрам
- `/assets/`
  - `main_render.jpg` — реальное фото оригинала банки (дизайнер сам вырезает при необходимости)
  - `logo_white.png` / `logo_dark.png` — логотипы Vitgem
  - `color-swatches.svg` — вектор палитры бренда
  - `/reference/` — превью текущих JPG (1.jpg–7.jpg), альтернативы (7-1.jpg, 8-1.png), ChatGPT-рендеры (2.png-7.png) и **8 премиум-вариантов из design pack** (slot1_premium_*, slot2_hero_*, slot4_premium_*, slot6_premium_*, slot7_premium_*, slot2_3_scene_only_bg)

## 7 слотов

| # | Концепт | Текст / Headline |
|---|---|---|
| 1 | MAIN — банка на белом | (без текста, Amazon main rule) |
| 2 | HERO — apothecary editorial | «14 ACTIVES, 1 DAILY GUMMY» |
| 3 | INGREDIENTS — формула + дозы | «HIGH-STRENGTH FORMULA» + 6 callout-pills |
| 4 | BENEFITS — body-map портрет | «SUPPORT, HEAD TO TOE» + 5 callouts |
| 5 | LIFESTYLE — marble kitchen | «Daily support through *menopause* & beyond» |
| 6 | TRUST — pedestal + бейджи | «TRUSTED BRITISH QUALITY» + 6 trust badges |
| 7 | GUMMY — raspberry splash (без банки) | «Just two a day · RASPBERRY · 30-DAY SUPPLY» |

## Воркфлоу

1. Заказчик сам генерит фон-сцены в ChatGPT/Nano Banana по «Промту фона» + «Промту композиции» (банки в промте НЕТ).
2. Дизайнер открывает сцену в Photoshop / Photopea, вырезает банку из `main_render.jpg`, композитит поверх.
3. Накладывает text overlay через vector type tool (не AI).
4. Экспорт `1.jpg` … `7.jpg` (2048×2048 sRGB JPEG q92).

## Версия

**v3** от 2026-05-25 — русифицированная premium-версия с интеграцией design pack.
