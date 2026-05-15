# ✏️ Interactive Trend Chart / 交互式趋势图

> A fully interactive trend chart web application. Click on the chart or enter coordinates to add data points, with support for multiple data series and chart types.

---

## 📸 Screenshots

![Interactive Trend Chart](screenshot.png)

---

## ✨ Features

- **🖱️ Click to Add Points** — Click anywhere on the chart area to instantly add a data point
- **⌨️ Coordinate Input** — Manually enter precise X/Y values
- **📈 Multiple Data Series** — Add, switch, and delete multiple trend lines with auto-assigned colors
- **📊 Chart Type Switching** — Toggle between Line Chart, Bar Chart, and Scatter Plot
- **↩️ Undo Support** — Ctrl+Z to undo the last action
- **📥 JSON Export** — Export all data as a JSON file
- **🗑️ Clear Options** — Clear current series or all data at once
- **🌙 Dark Theme** — Modern dark UI design
- **📱 Responsive** — Works on desktop and mobile devices

---

## 🚀 Quick Start

No build tools or dependencies required. Simply open the HTML file in a browser:

```bash
# Option 1: Open directly
open trend-chart.html

# Option 2: Use a local server (recommended)
python3 -m http.server 8080
# Then visit http://localhost:8080/trend-chart.html
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling & responsive layout |
| JavaScript (ES6+) | Interactivity & chart logic |
| [Chart.js](https://www.chartjs.org/) | Chart rendering |

---

## 📖 Usage Guide

### Adding Data Points
1. **Click Mode** (default): Simply click anywhere on the chart canvas
2. **Input Mode**: Switch to "输入坐标" mode, enter X and Y values, then click "添加" or press Enter

### Managing Series
- Click a series in the sidebar to select it (highlighted with purple border)
- New points are added to the **active** series
- Click "×" to delete a series (minimum 1 series required)
- Enter a name and click "添加" to create a new series

### Chart Types
- **折线图 (Line)**: Classic trend line with area fill
- **柱状图 (Bar)**: Vertical bars for comparison
- **散点图 (Scatter)**: Individual data points without connecting lines

### Keyboard Shortcuts
| Shortcut | Action |
|---|---|
| `Ctrl + Z` | Undo last point |

---

## 📁 File Structure

```
├── trend-chart.html    # Main application (single file)
├── README.md           # This file
└── screenshot.png      # Screenshot image
```

---

## 📄 License

MIT License — feel free to use, modify, and distribute.

---

## 🌍 多语言说明 / Multilingual README

This README is available in the 6 official languages of the United Nations:

| Language | 语言 | Section |
|---|---|---|
| 🇨🇳 Chinese | 中文 | [中文说明](#-中文说明) |
| 🇬🇧 English | 英文 | [English](#-english) |
| 🇫🇷 French | 法语 | [Français](#-français) |
| 🇪🇸 Spanish | 西班牙语 | [Español](#-español) |
| 🇷🇺 Russian | 俄语 | [Русский](#-русский) |
| 🇸🇦 Arabic | 阿拉伯语 | [العربية](#-العربية) |

---
---

# 🇨🇳 中文说明

## 简介

交互式趋势图是一个基于网页的可视化工具。您可以通过**点击图表**或**输入坐标**来自定义数据点，支持多条数据系列和多种图表类型。

## 功能特性

- **点击添加** — 直接在图表上点击即可添加数据点
- **坐标输入** — 手动输入精确的 X/Y 坐标值
- **多系列** — 支持添加、切换、删除多条趋势线
- **图表切换** — 折线图、柱状图、散点图一键切换
- **撤销操作** — 支持 Ctrl+Z 撤销
- **数据导出** — 一键导出 JSON 格式数据
- **暗色主题** — 现代化深色界面设计
- **响应式布局** — 适配桌面端和移动端

## 快速开始

无需安装任何依赖，直接在浏览器中打开 HTML 文件即可使用：

```bash
# 方式一：直接打开
open trend-chart.html

# 方式二：使用本地服务器（推荐）
python3 -m http.server 8080
# 访问 http://localhost:8080/trend-chart.html
```

## 使用方法

1. **点击模式**（默认）：直接点击图表区域添加数据点
2. **输入模式**：切换到"输入坐标"，输入 X 和 Y 值后点击"添加"
3. **切换系列**：在左侧面板点击不同系列名称来切换当前活跃系列
4. **切换图表**：在"图表类型"区域选择折线图、柱状图或散点图

## 技术栈

HTML5 + CSS3 + JavaScript + Chart.js

---
---

# 🇬🇧 English

## Overview

Interactive Trend Chart is a web-based visualization tool. Customize data points by **clicking on the chart** or **entering coordinates**, with support for multiple data series and chart types.

## Features

- **Click to Add** — Click anywhere on the chart to add data points instantly
- **Coordinate Input** — Enter precise X/Y values manually
- **Multiple Series** — Add, switch between, and delete multiple trend lines
- **Chart Type Switching** — Toggle between Line, Bar, and Scatter charts
- **Undo** — Ctrl+Z to undo the last action
- **Data Export** — Export all data as JSON
- **Dark Theme** — Modern dark UI
- **Responsive** — Works on desktop and mobile

## Quick Start

No dependencies required. Open the HTML file in any modern browser:

```bash
open trend-chart.html
# Or use a local server:
python3 -m http.server 8080
```

## Tech Stack

HTML5 + CSS3 + JavaScript + Chart.js

---
---

# 🇫🇷 Français

## Aperçu

Le graphique de tendance interactif est un outil de visualisation basé sur le web. Personnalisez les points de données en **cliquant sur le graphique** ou en **entrant des coordonnées**, avec prise en charge de plusieurs séries de données et types de graphiques.

## Fonctionnalités

- **Ajout par clic** — Cliquez n'importe où sur le graphique pour ajouter un point de données
- **Saisie de coordonnées** — Entrez manuellement des valeurs X/Y précises
- **Séries multiples** — Ajoutez, changez et supprimez plusieurs lignes de tendance
- **Types de graphiques** — Basculez entre graphique linéaire, à barres et à points
- **Annuler** — Ctrl+Z pour annuler la dernière action
- **Export de données** — Exportez toutes les données au format JSON
- **Thème sombre** — Interface moderne en mode sombre
- **Responsive** — Fonctionne sur bureau et mobile

## Démarrage rapide

Aucune dépendance requise. Ouvrez le fichier HTML dans un navigateur moderne :

```bash
open trend-chart.html
# Ou utilisez un serveur local :
python3 -m http.server 8080
```

## Technologies

HTML5 + CSS3 + JavaScript + Chart.js

---
---

# 🇪🇸 Español

## Resumen

El gráfico de tendencia interactivo es una herramienta de visualización basada en la web. Personalice los puntos de datos **haciendo clic en el gráfico** o **ingresando coordenadas**, con soporte para múltiples series de datos y tipos de gráficos.

## Características

- **Agregar por clic** — Haga clic en cualquier lugar del gráfico para agregar un punto de datos
- **Entrada de coordenadas** — Ingrese valores X/Y precisos manualmente
- **Múltiples series** — Agregue, cambie y elimine múltiples líneas de tendencia
- **Tipos de gráficos** — Alterne entre gráfico de líneas, de barras y de dispersión
- **Deshacer** — Ctrl+Z para deshacer la última acción
- **Exportar datos** — Exporte todos los datos en formato JSON
- **Tema oscuro** — Interfaz moderna en modo oscuro
- **Responsivo** — Funciona en escritorio y dispositivos móviles

## Inicio rápido

No se requieren dependencias. Abra el archivo HTML en cualquier navegador moderno:

```bash
open trend-chart.html
# O use un servidor local:
python3 -m http.server 8080
```

## Tecnologías

HTML5 + CSS3 + JavaScript + Chart.js

---
---

# 🇷🇺 Русский

## Обзор

Интерактивный график тенденций — это веб-инструмент визуализации. Настройте точки данных, **нажимая на график** или **вводя координаты**, с поддержкой нескольких рядов данных и типов графиков.

## Возможности

- **Добавление по клику** — Нажмите в любом месте графика, чтобы добавить точку данных
- **Ввод координат** — Вручную вводите точные значения X/Y
- **Несколько рядов** — Добавляйте, переключайте и удаляйте несколько линий тренда
- **Типы графиков** — Переключение между линейным, столбчатым и точечным графиками
- **Отмена** — Ctrl+Z для отмены последнего действия
- **Экспорт данных** — Экспорт всех данных в формате JSON
- **Тёмная тема** — Современный тёмный интерфейс
- **Адаптивность** — Работает на десктопе и мобильных устройствах

## Быстрый старт

Зависимости не требуются. Откройте HTML-файл в любом современном браузере:

```bash
open trend-chart.html
# Или используйте локальный сервер:
python3 -m http.server 8080
```

## Технологии

HTML5 + CSS3 + JavaScript + Chart.js

---
---

# 🇸🇦 العربية

## نظرة عامة

الرسم البياني التفاعلي للاتجاهات هو أداة تصور قائمة على الويب. قم بتخصيص نقاط البيانات **بالنقر على الرسم البياني** أو **إدخال الإحداثيات**، مع دعم سلاسل بيانات متعددة وأنواع رسوم بيانية مختلفة.

## الميزات

- **إضافة بالنقر** — انقر في أي مكان على الرسم البياني لإضافة نقطة بيانات
- **إدخال الإحداثيات** — أدخل قيم X/Y الدقيقة يدويًا
- **سلاسل متعددة** — أضف وبدّل واحذف خطوط اتجاه متعددة
- **أنواع الرسوم البيانية** — التبديل بين الرسم الخطي والشريطي والمنتشر
- **تراجع** — Ctrl+Z للتراجع عن آخر إجراء
- **تصدير البيانات** — تصدير جميع البيانات بتنسيق JSON
- **الوضع الداكن** — واجهة حديثة بتصميم داكن
- **تصميم متجاوب** — يعمل على سطح المكتب والأجهزة المحمولة

## البدء السريع

لا توجد متطلبات مسبقة. افتح ملف HTML في أي متصفح حديث:

```bash
open trend-chart.html
# أو استخدم خادمًا محليًا:
python3 -m http.server 8080
```

## التقنيات

HTML5 + CSS3 + JavaScript + Chart.js
