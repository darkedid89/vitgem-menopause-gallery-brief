# Style Audit — единство стиля 7-сета Vitgem Menopause (v3)

Анализ визуальной семьи между 7 финальными слотами по 6 параметрам.

---

## Таблица параметров

| Параметр | 1 MAIN | 2 HERO | 3 INGRED | 4 BENEFITS | 5 LIFESTYLE | 6 TRUST | 7 GUMMY |
|---|---|---|---|---|---|---|---|
| Доминант фона | чисто белый | blush gradient | бежевый камень | pink-mauve gradient | белый мрамор кухни | blush-mauve gradient | cream + raspberry red |
| Источник света | даун-фронт | warm key слева | soft top | soft front | окно справа | даун soft | warm splash |
| Тип сцены | studio | tabletop | tabletop | портрет | lifestyle | studio | macro food |
| Aubergine акцент | ✅ этикетка | ✅ заголовок | ✅ pills | ✅ callouts | ✅ заголовок | ✅ header | ❌ нет |
| Gold акцент | ✅ этикетка | ✅ band | ✅ pills | ❌ | ❌ | ✅ icons | ❌ |
| Type-система | label only | DM Sans + Playfair | DM Sans | DM Sans | DM Sans + Playfair | DM Sans | DM Sans + Playfair |

---

## Несогласованности — что выровнять дизайнеру

### 1. Slot 5 (белый мрамор кухни) — слишком яркий vs остальные
Светлая кухня контрастирует с тёплым mauve-семейством слотов 4 и 6.
**Решение:** post-tone (warm temp +5, exposure −3, лёгкий aubergine vignette).

### 2. Slot 7 (raspberry red splash) — резкий контраст к cream/mauve семье
**Решение:** оправдано как «food beauty» слот; разместить в конце carousel (Amazon позиция 7).

### 3. Slot 4 (тёплый pink-mauve) vs Slot 3 (нейтральный beige stone)
**Решение:** подтянуть фон Slot 4 к Slot 3 — нейтральный + лёгкий mauve gradient в углах.

### 4. Aubergine `#5A2F4E` — везде ✅
Главный объединяющий цвет (этикетка банки + заголовки в большинстве слотов).

### 5. Gold `#D8B060` — есть в 1, 2, 3, 6; отсутствует в 4, 5, 7
**Решение:** добавить hairline gold подчёркивание на 4 (callout-линии) и 5 (под headline) — для family-look.

### 6. Шрифты ✅
Все на DM Sans + Playfair Italic accents — единая type-система.

---

## Verdict

Семья **достаточно консистентна** (~90% общих токенов). Slot 5 и Slot 4 нуждаются в лёгкой post-tonировке для финального лоска. Перечисленные доработки — задача дизайнера, не блокер для предварительной загрузки на Amazon.

---

## Post-tone рекомендации (Adobe Lightroom / Photoshop)

Применить ко **всем** финальным JPG для единой семьи:
- **Color temp:** +3 — +5 (теплее)
- **Tint:** +2 (чуть в magenta)
- **Exposure:** −0.1 (slot 5 −0.3)
- **Highlights:** −10
- **Shadows:** +5
- **Vibrance:** +8
- **Saturation:** −3
- **Vignette:** −8 (мягкий aubergine cast в углах)
- **Grain:** amount 8, size 20, roughness 50
