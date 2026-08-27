# 🤖 VersaBot | All-in-One Telegram Bot

An intelligent, cloud-based, multi-purpose Telegram bot designed to solve everyday tasks without downloading heavy applications.

---

## 🎯 Project Goal

We've all been there: installing heavy apps—sometimes hundreds of megabytes—just to perform a tiny task like generating a QR code or converting a file. 

VersaBot was created to eliminate app clutter and device storage waste. It provides a lightweight, comprehensive, and lightning-fast tool directly inside Telegram to handle everyday micro-tasks seamlessly.

---

## ⚡ Technical Overview & Architecture

Built with Python using the modern **aiogram 3.x** framework, the bot runs on a fuAsynchronous (Async)c)** architecture:

High Concurrency & Ultra-Fast Response:e:** Unlike traditional synchronous (Sync) bots, VersaBot processes hundreds of simultaneous user requests without bottlenecks or queue delays.
* High Stability & Efficiency:y:** Optimized resource management ensures a smooth, real-time user experience under heavy load.

---

## ✨ Features & Capabilities

Simply send /start to access the interactive main menu. Here is what VersaBot can do for you:

### 🔳 1. Advanced QR Code Generator
Convert any text or URL into a custom QR code instantly. The standout feature heremulti-format output selectionon**:

* Raster Formats (PNG / JPG):):** Perfect for general use, social media sharing, and crisp pixel displays.
*Web Format (WebP):):** Ultra-lightweight and optimized for websites and web apps.
*Vector Format (SVG - Featured):):** Scalable vector output with infinite quality—ideal for print, posters, business cards, and advertising billboards without any pixelation.Workflow:w:** Select QR Code Tool ➡️ Send Text or Link ➡️ Choose Format (PNG, JPG, WebP, SVG) ➡️ Receive File Instantly.

---

### 📅 2. Advanced Date Converter (Jalali ⇄ Gregorian) + Day of Week
Easily convert dates between the Persian (Jalali) and Gregorian calendars with just a few taps:

*Bi-directional Conversion:n:** Convert Jalali to Gregorian or vice-versa.
* Day-of-Week Detection:n:** Automatically calculates and displays the exact day of the week (e.g., Saturday, Friday).
*Input Validation:n:** Built-in error handling alerts users if an invalid date or format is sent, guiding them toward correct input.

> 💡 *Pro Tip: Use English numerals for input to ensure maximum processing speed.*

---

### ✂️ 3. Smart Background Removal
Separate subjects from photo backgrounds with precision rivaling specialized image editing applications:

*Accurate Edge Detection:n:** Retains intricate facial and object details while cutting out the background.
* Image Output (PNG):):** Transparent PNG file ready to be placed on any background or used in graphic designs.
*Sticker Mode (WebP - Special Feature):):** Choose WebP output to automatically convert your transparent image intcustom Telegram stickerer**!

---

### 📄 4. Smart Image to PDF Converter
Combine multiple images into a clean, single PDF document without installing heavy scanner apps:

*High Capacity:y:** Convup to 15 imageses** per PDF document (no daily usage limit).
*Live Progress Counter:r:** The bot tracks uploaded images and shows remaining capacity in real time.
Auto & Manual Generation:n:** PDF auto-generates upon reaching 15 photos, or manually whenever you tap the "Build PDF" button.

> 💡 *Note: Send images one by one (single files) rather than as an album to guarantee exact page ordering.*

---

### 💎 5. Real-Time Market Prices (Gold, Currency & Commodities)
Get real-time financial market data with a single tap—no need to browse multiple websites:

*Gold & Coins Market (in IRR/Toman):):**
  * 18K and 24K Gold prices
  * Emami (New) and Bahar Azadi (Old) Gold Coins
  * Half & Quarter Coins
  * 925 Sterling Silver
*Global Markets & Forex (in USD):):**
  * Live USD Rate
  * Spot Gold (XAU/USD) & Silver (XOW/USD)
  * Brent Crude Oil

---

### 💬 6. User Feedback & Reviews
Your voice drives future development! Tapping the feedback button redirects you to a web page where you can submit your email, suggestions, and critiques directly to the developer.

---

## 🚀 Getting Started

Start using the bot on Telegram right now:

👉 [Launch VersaBot on Telegram](http://t.me/versa10bot)

---

## 🛠️ Built With

* 🐍 Python - Core programming language
* ⚡ Aiogram 3.x - Modern asynchronous Telegram framework
* 🗄️ PostgreSQL - Production-grade database for high concurrency & security
* 🔄 n8n - Workflow automation & data pipeline integration

---

## 🔐 Privacy Policy

We take user privacy and security seriously. Learn more about how we handle data in [PRIVACY.md](./PRIVACY.md).