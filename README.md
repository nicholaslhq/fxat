# 📈 FXAT | FX-Adjusted Ticker

**Visualize the real impact of currency fluctuations on your global investments.**

![Single File](https://img.shields.io/badge/Architecture-Single--File-brightgreen)
![Vanilla JS](https://img.shields.io/badge/Logic-Vanilla--JS-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🔍 Overview

When investing in foreign markets, your returns aren't just about the stock price—they're deeply tied to the exchange rate. A 10% gain in a US stock can be completely wiped out if the USD weakens by 10% against your local currency.

**FXAT (FX-Adjusted Ticker)** is a lightweight, frontend-only dashboard that helps you see the "true" performance of any ticker in any currency. It fetches real-time data and historical prices to calculate exactly how your investment has fared after adjusting for FX risk.

## ✨ Key Features

-   🚀 **Zero Install**: Runs entirely as a single `index.html` file. No servers, no `npm install`, no setup.
-   💹 **Multi-Currency Comparison**: compare the performance of a stock across multiple target currencies simultaneously.
-   🌓 **Dual-Axis Visualization**: Toggle a base-currency overlay to see exactly where the stock moved versus where the currency moved.
-   📊 **Performance Statistics**: Get clear "Starting Value", "Ending Value", and "Total Return" metrics for each currency.
-   🕒 **Granular Time Ranges**: Navigate from 1-month to "Max" history with ease.
-   📱 **Fully Responsive**: Professionally designed for both desktop and mobile viewing with a modern, clean UI.
-   📄 **Data Transparency**: View the raw underlying pricing and FX data in a collapsible, searchable table.
-   🖱️ **Interactive Plotting**: Click and drag to measure gains between any two points. Double-click to reset.

## 🛠️ Installation & Usage

### Running Locally
Since FXAT is a self-contained web app, getting started takes seconds:

1.  **Download** the `index.html` file.
2.  **Open** it in any modern web browser.
3.  **Enter** a ticker (e.g., `AAPL`) and your target currency (e.g., `MYR,EUR,GBP`).
4.  **Click** "View Chart" to see the magic happen!

> [!TIP]
> You can host this file for free on **GitHub Pages**, **Vercel**, or **Netlify** by simply uploading the single `index.html` file!

## 💡 How It Works

FXAT leverages public financial APIs to provide a seamless experience:
-   **Data Source**: Fetches historical stock and FX data via Yahoo Finance.
-   **Proxy**: Uses `corsproxy.io` to handle cross-origin requests safely.
-   **Visualization**: Powered by **Plotly.js** for high-performance, interactive charting.
-   **Logic**: All calculations are performed on-the-fly in your browser using Vanilla JavaScript.

## ❓ FAQ

**Q: Is the data real-time?**

A: Data is fetched directly from Yahoo Finance and is typically subject to standard market delays (approx. 15-20 minutes).

**Q: Does it store any of my data?**

A: No. FXAT is entirely client-side. Your ticker symbols and currency choices never leave your browser, except to fetch data from the public APIs.

**Q: Can I use this for crypto?**

A: Yes! As long as the ticker is supported by Yahoo Finance (e.g., `BTC-USD`), it will work.

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features or improvements, feel free to open an issue or submit a pull request.

## 🌟 Inspiration & Credits

FXAT is inspired by and built with reference to the [TickerFX](https://github.com/LeonidasTMT/TickerFX) project by [LeonidasTMT](https://github.com/LeonidasTMT). Credits to the original project for the foundational idea!

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<p align="center">
  Built with ❤️ for global investors
</p>
