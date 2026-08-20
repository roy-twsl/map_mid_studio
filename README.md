# 🧠 Mind Map Studio (مایند مپ استودیو)

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat-square)
![Dependencies](https://img.shields.io/badge/dependencies-Zero%20(Pure%20Vanilla%20JS)-emerald.svg?style=flat-square)
![Offline](https://img.shields.io/badge/offline-100%25%20Local-purple.svg?style=flat-square)

**A professional, minimal, and 100% offline Mind Mapping web application built with pure Vanilla JavaScript.**  
**وب‌اپلیکیشن مستقل، مینیمال و ۱۰۰٪ آفلاین برای ساخت و مدیریت نقشه‌های ذهنی.**

[English](#-english) • [فارسی](#-فارسی-persian)

</div>

---

## 🌐 English

### Overview
**Mind Map Studio** is an ultra-fast, zero-dependency, single-file Mind Mapping application. It is engineered with a focus on clean design, strict bidirectional (RTL & LTR) text rendering, mathematical symmetrical auto-balancing, proprietary encrypted file persistence (`.pmm`), and pixel-perfect offline Canvas & PDF exports.

### ✨ Key Features
- **100% Standalone & Offline-First:** Zero external CDNs, zero cloud APIs, and zero tracking. Works entirely on your local machine out-of-the-box.
- **Strict Bilingual Isolation (FA & EN):** Seamlessly handles mixed Persian and English sentences with isolated `unicode-bidi` direction without phrase inversion.
- **Buzan's 360° Clockwise Layout:** Automatically distributes branches starting from Top-Right (1 o'clock) down to Bottom-Right, and continuing up through Bottom-Left to Top-Left in an uninterrupted circular flow.
- **Dynamic Weight-Balanced Auto-Layout:** Balances cumulative subtree heights across both sides to ensure optical 50/50 symmetry.
- **Exact Geometric Midpoint Centering:** The Root Node is placed dead-center relative to the canvas and all child branches.
- **High-Fidelity Offline Export (PNG & PDF):** 100% client-side vector/raster renderer that generates crisp 300 DPI exports matching the live screen.
- **Fullscreen Image Lightbox:** Embedded Base64 images with infinite pan and smooth scroll-zoom.
- **Encrypted Local Persistence (`.pmm`):** Project files are secured with a proprietary client-side cipher that embeds all assets permanently.
- **Custom Context Menu & Protection:** Right-click context menus on nodes, safe recursive deletion confirmations, and blocked intrusive browser shortcuts.
- **Full Undo / Redo:** Complete history stack with `Ctrl+Z` and `Ctrl+Y`.

---

### ⌨️ Keyboard Shortcuts

| Shortcut | Description |
| :--- | :--- |
| `Tab` | Add Smart Sub-node (Right or Left dynamically) |
| `Shift + Enter` | Add Sibling Branch |
| `Enter` / `F2` | Edit Selected Node Text |
| `Escape` | Finish Editing and Select Node |
| `Ctrl + Z` / `Ctrl + Y` | Undo / Redo |
| `Ctrl + I` | Open Icon & Emoji Library |
| `Alt + X` | Remove Icon from Active Node |
| `↑ ↓ ← →` | Spatial 2D Node Navigation |
| `Delete` | Delete Node (Protected on Root) |
| `Ctrl + S` | Save Encrypted Project File (`.pmm`) |
| `Ctrl + P` | Open PDF Export Dialog |
| `Ctrl + D` | Toggle Dark / Light Theme |

---

## 🇮🇷 فارسی (Persian)

### معرفی
**مایند مپ استودیو** یک ابزار تک‌فایلی، مدرن و کاملاً آفلاین برای طراحی نقشه‌های ذهنی است. این برنامه بدون نیاز به اینترنت و بدون استفاده از هیچ‌گونه کتابخانه خارجی توسعه داده شده و از قابلیت‌هایی نظیر چیدمان متقارن ساعت‌گرد، رمزنگاری فایل پروژه و خروجی کریستالی عکس و PDF پشتیبانی می‌کند.

### ✨ ویژگی‌های کلیدی
- **کاملاً آفلاین و مستقل (Zero Dependency):** بدون نیاز به اتصال اینترنت یا سرور خارجی؛ تمامی پردازش‌ها در حافظه مرورگر سیستم انجام می‌شود.
- **پشتیبانی بدون نقص از ترکیب فارسی و انگلیسی:** متون ترکیبی (مانند جملات دارای کلمات انگلیسی) بدون به‌هم‌ریختگی و با رعایت کامل تراز راست‌به‌چپ (RTL) رندر می‌شوند.
- **چیدمان استاندارد ساعت‌گرد (قانون ۳۶۰ درجه تونی بوزان):** شاخه‌ها به ترتیب ایجاد از بالا-راست آغاز شده، به پایین-راست رفته و از پایین-چپ به بالا-چپ چرخه را تکمیل می‌کنند.
- **تعادل وزنی پویا (Dynamic Weight Balancing):** تقسیم هوشمند شاخه‌ها بر اساس ارتفاع واقعی برای ایجاد تقارن ۵۰/۵۰ میان سمت راست و چپ مپ.
- **تراز هندسی دقیق نود ریشه:** قرارگیری نود اصلی دقیقاً بر مرکز عمودی و افقی صفحه.
- **خروجی باکیفیت و بدون باگ (PNG و PDF):** رندرینگ مستقل روی بوم با مقیاس ۳ برابری و انطباق ۱۰۰٪ با آنچه در صفحه مشاهده می‌کنید.
- **لایت‌باکس تمام‌صفحه تصاویر:** قابلیت زوم آزادانه با اسکرول ماوس و حرکت (Pan) روی تصاویر تعبیه‌شده.
- **فرمت فایل انحصاری رمزنگاری‌شده (`.pmm`):** ذخیره تمام ساختار مپ و رشته‌های باینری تصاویر به‌صورت مستقل برای بازگشایی در هر سیستم دیگر.
- **سیستم بازگشت به قبل و بعد (Undo / Redo):** تاریخچه ۵۰ مرحله‌ای برای تمام تغییرات با `Ctrl+Z` و `Ctrl+Y`.

---

### ⌨️ کلیدهای میانبر سریع

| کلید میانبر | عملکرد |
| :--- | :--- |
| `Tab` | افزودن زیرشاخه هوشمند (راست یا چپ خودکار) |
| `Shift + Enter` | افزودن شاخه هم‌سطح |
| `Enter` یا `F2` | ویرایش متن نود انتخابی |
| `Escape` | اتمام ویرایش و بازگشت به حالت انتخاب نود |
| `Ctrl + Z` / `Ctrl + Y` | بازگشت به قبل / بعد (Undo / Redo) |
| `Ctrl + I` | باز کردن کتابخانه آیکون‌ها و ایموجی |
| `Alt + X` | حذف آیکون از نود فعال |
| `↑ ↓ ← →` | جابه‌جایی انتخاب میان نودها در فضای ۲ بعدی |
| `Delete` | حذف نود انتخابی (نود اصلی محافظت‌شده است) |
| `Ctrl + S` | ذخیره فایل پروژه با رمزنگاری اختصاصی |
| `Ctrl + P` | باز کردن پنجره تولید و دانلود سند PDF |
| `Ctrl + D` | تغییر تم بین حالت روشن و تاریک |

---

### 🛠 Tech Stack (تکنولوژی‌های استفاده‌شده)
- **Pure HTML5 / CSS3** (Custom Properties, Flexbox, Positioning, Bidi Isolation)
- **Vanilla JavaScript (ES6+)** (Canvas API, SVG Vector Engine, Web TextEncoder/Decoder, Blob API, Offline Pure PDF 1.4 Byte Stream Compiler)

---

### 📄 License
This project is open-source and available under the **MIT License**.
