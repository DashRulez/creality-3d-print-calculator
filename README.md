# 3D Print Cost Calculator (Калькулятор 3D-друку)

A simple, static HTML/CSS/JS calculator designed to help estimate the cost of 3D printing jobs. Design inspired by Creality. It uses `localStorage` to save user presets and filament libraries directly in the browser.

## 🚀 Live Demo

[**View the live calculator here**](https://dashrulez.github.io/creality-3d-print-calculator/calculator.html)


## ✨ Features (Особливості)

* **Printer Presets:** Save and load different printer profiles (cost, power, lifespan).
* **Filament Library:** Manage a custom library of filaments with their prices and weights.
* **Detailed Costing:** Calculates costs based on:
    * Machine Hour Rate (MHR)
    * Material cost (multi-material support)
    * Manual post-processing time
    * Risk/failure percentage
* **Markup Calculation:** Easily add a markup to get the final client price.
* **Bilingual:** Supports Ukrainian (UA) and English (EN).
* **No Server Needed:** Runs entirely in the browser and saves all data to `localStorage`.

## 🛠️ How to Use (Як використовувати)

1.  **Download:** Download the `calculator.html` file.
2.  **Open:** Open the file in any modern web browser.
3.  **Configure:**
    * Go to **Printer Settings** and input your printer's details, then click "Save".
    * Go to **Used Materials** -> **Manage Filaments** to add the filaments you own.
4.  **Calculate:**
    * Add one or more materials used for the print and set their weight (in grams).
    * Set the **Print Time** from your slicer.
    * Adjust other fields like post-processing time, risk, and markup.
5.  **Get Price:** The **Price for Client** is calculated automatically.
