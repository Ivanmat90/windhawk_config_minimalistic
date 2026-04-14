[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
# EN
## 🔧 My Windhawk configuration:

***Author of all mods in this configuration:*** [m417z](https://m417z.com/)
***Works on: Windhawk 1.7, Windows 11 24H2***

> [!warning] This configuration will not work or will work partially on Windows 10

---
### 🚀 How to apply?

1. Install the mod via Windhawk's mod store
2. Open **"Advanced"** in the mod settings
3. Copy the JSON from the corresponding section
4. Paste → **"Apply"**

---
### 1. Better file sizes in Explorer details

*Shows real folder and file sizes via Everything.*

> [!tip] [Everything](https://voidtools.com/) must be installed with indexing enabled: Tools — Options — Indexes — Enable "Folder sizes".

```json
{
  "calculateFolderSizes": "everything",
  "sortSizesMixFolders": 1,
  "disableKbOnlySizes": 1,
  "useIecTerms": 0
}
```

### 2. Remove Taskbar Window Suffixes

*Removes "— File Explorer" from window titles on the taskbar.*

```json
{
  "suffixRemovalMode": "fileExplorerOnly",
  "suffixRules[0].processIdentifier": "",
  "suffixRules[0].search": "",
  "suffixRules[0].replace": ""
}
```

### 3. Start Menu Size

*Start menu height 425 pixels (auto width).*

```json
{
  "width": 0,
  "height": 425,
  "searchWidth": 0,
  "searchHeight": 0
}
```

### 4. Taskbar height and icon size

*Thin taskbar (35px) and small icons.*

```json
{
  "TaskbarHeight": 35,
  "IconSize": 18,
  "TaskbarButtonWidth": 31,
  "IconSizeSmall": 16,
  "TaskbarButtonWidthSmall": 32
}
```

### 5. Windows 11 File Explorer Styler

*Leaves only the address/search bar.*

```json
{
  "theme": "AddressSearchOnly",
  "backgroundTranslucentEffect": "",
  "backgroundTranslucentEffectRegion": "",
  "styleConstants[0]": "",
  "controlStyles[0].target": "",
  "controlStyles[0].styles[0]": "",
  "themeResourceVariables[0]": "",
  "explorerFrameContainerHeight": 0,
  "xamlDiagnosticsHandling": "alert"
}
```

### 6. Windows 11 Start Menu Styler

*Removes the "Recommendations" block from the Start menu.*

```json
{
  "theme": "NoRecommendedSection",
  "disableNewStartMenuLayout": "",
  "styleConstants[0]": "",
  "controlStyles[0].target": "",
  "controlStyles[0].styles[0]": "",
  "themeResourceVariables[0]": "",
  "webContentStyles[0].target": "",
  "webContentStyles[0].styles[0]": "",
  "webContentCustomJs": ""
}
```

---
### ⚠️ Notes

- Mods #4 and #6 may conflict with other mods (e.g., Vertical taskbar)
- If you have a 4K screen, increase `height` in mod #3 to 600–700
- To revert — just delete the JSON from "Advanced" and apply again


# RU
## 🔧 Моя конфигурация для Windhawk:

***Автор всех модов в этой конфигурации:*** [m417z](https://m417z.com/)
***Работает на: Windhawk 1.7, Windows 11 24H2***

> [!warning] Данная конфигурация на Windows 10 не будет работать или работать частично

---
### 🚀 Как применить?

1. Установите мод через магазин Windhawk
2. Откройте **«Дополнительно»** в настройках мода
3. Скопируйте JSON из нужного раздела
4. Вставьте → **«Применить»**

---
## 1. Better file sizes in Explorer details

*Показывает реальные размеры папок и файлов через Everything.*

> [!tip] Должен быть установлен [Everything](https://voidtools.com/) с включённым индексированием: Сервис — Настройки — Индексирование — Поставить галочку "Размеры папок".

```json
{
  "calculateFolderSizes": "everything",
  "sortSizesMixFolders": 1,
  "disableKbOnlySizes": 1,
  "useIecTerms": 0
}
```

### 2. Remove Taskbar Window Suffixes

*Убирает «— Проводник» в заголовках окон на панели задач.*

```json
{
  "suffixRemovalMode": "fileExplorerOnly",
  "suffixRules[0].processIdentifier": "",
  "suffixRules[0].search": "",
  "suffixRules[0].replace": ""
}
```

### 3. Start Menu Size

*Высота Пуска 425 пикселей (ширина авто).*

```json
{
  "width": 0,
  "height": 425,
  "searchWidth": 0,
  "searchHeight": 0
}
```

### 4. Taskbar height and icon size

*Тонкая панель (35px) и маленькие иконки*

```json
{
  "TaskbarHeight": 35,
  "IconSize": 18,
  "TaskbarButtonWidth": 31,
  "IconSizeSmall": 16,
  "TaskbarButtonWidthSmall": 32
}
```

### 5. Windows 11 File Explorer Styler

*Оставляет только строку адреса/поиска.*

```json
{
  "theme": "AddressSearchOnly",
  "backgroundTranslucentEffect": "",
  "backgroundTranslucentEffectRegion": "",
  "styleConstants[0]": "",
  "controlStyles[0].target": "",
  "controlStyles[0].styles[0]": "",
  "themeResourceVariables[0]": "",
  "explorerFrameContainerHeight": 0,
  "xamlDiagnosticsHandling": "alert"
}
```

### 6. Windows 11 Start Menu Styler

*Убирает блок «Рекомендации» в Пуске.*

```json
{
  "theme": "NoRecommendedSection",
  "disableNewStartMenuLayout": "",
  "styleConstants[0]": "",
  "controlStyles[0].target": "",
  "controlStyles[0].styles[0]": "",
  "themeResourceVariables[0]": "",
  "webContentStyles[0].target": "",
  "webContentStyles[0].styles[0]": "",
  "webContentCustomJs": ""
}
```

---
### ⚠️ Замечания

- Моды №4 и №6 могут конфликтовать с другими модами (например, Vertical taskbar)
- Если экран 4K, увеличьте `height` в моде №3 до 600–700
- Для отката — просто удалите JSON из «Дополнительно» и примените заново

# LICENSE

## 📄 License (for the instruction text only)

This instruction (text, descriptions, translations, structure) is licensed under  
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**You are free to:**  
- Share — copy and redistribute the material in any medium or format  
- Adapt — remix, transform, and build upon the material for any purpose, even commercially  

**Under the following term:**  
- Attribution — You must give appropriate credit to the author of this instruction.

**Author:** Ivanmat90  
**Date:** 2026

*The JSON mod configurations belong to their respective authors (m417z and others) and are subject to Windhawk's licensing.*
