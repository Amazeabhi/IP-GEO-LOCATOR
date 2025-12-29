# 🌐 IP Intelligence Pro

A high-performance, professional **IP Geolocation Explorer** built with modern web technologies. This tool allows users to instantly retrieve detailed intelligence about any IP address, including ISP data, geographic location with flag indicators, and a persistent search history.
## 🚀 Live Demo

Experience the tool live without any setup:

[![Launch App](https://img.shields.io/badge/Launch_App-🚀-blue?style=for-the-badge&logo=rocket)](https://amazeabhi.github.io/IP-GEO-LOCATOR/)

---



## ✨ Key Features

* **Real-time Lookup:** Fetches accurate country, region, city, and ISP details using the IPinfo API.
* **Persistent Search History:** Automatically saves your last 5 searches using browser `localStorage`.
* **Smart Dark Mode:** Seamlessly toggle between Light and Dark themes with a modern switch (persists on reload).
* **Dynamic Flag Icons:** Displays the official country flag for every searched IP via FlagCDN.
* **Input Validation:** Robust Regex validation for IPv4 and IPv6 addresses to prevent unnecessary API calls.
* **Responsive Design:** Fully optimized for Mobile, Tablet, and Desktop using Tailwind CSS.
* **One-Click Map:** Deep link integration to view exact coordinates on Google Maps.

---

## 🚀 Tech Stack

* **Frontend:** HTML5, Tailwind CSS (Utility-first CSS)
* **Icons:** FontAwesome 6
* **Logic:** Vanilla JavaScript (ES6+), Fetch API
* **API:** [IPinfo.io](https://ipinfo.io) (Geolocation Data source)
* **Assets:** [FlagCDN](https://flagcdn.com) (Vector Flags)

---

## 🛠️ Setup & Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/ip-intelligence-pro.git](https://github.com/yourusername/ip-intelligence-pro.git)
    ```

2.  **Get your API Token:**
    * Sign up at [IPinfo.io](https://ipinfo.io/signup) to get a free API token (Free tier supports 50k requests/month).

3.  **Configure the Token:**
    * Open `index.html`.
    * Locate the line: `const API_TOKEN = 'your_token_here';`
    * Replace it with your actual alphanumeric token.

4.  **Launch:**
    * Simply open `index.html` in any modern web browser. No server setup is required!

---

## 📸 Interface Preview

| Feature | Description |
| :--- | :--- |
| **Search Bar** | Supports IP addresses and automatic detection of your own IP. |
| **History Sidebar** | Quick access to your recently searched addresses. |
| **Theme Toggle** | Dedicated button to switch between light and dark visual modes. |

---

## 📂 Project Structure

```text
.
├── index.html          # Core application (Logic, Styles, and UI)
└── README.md           # Documentation
