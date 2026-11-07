# 💱 Currency Converter – Real-Time Exchange Rates

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667EEA,100:764BA2&height=190&section=header&text=Currency%20Converter&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Convert%20Currencies%20with%20Ease&descAlignY=60&descSize=17" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/API-Integration-764BA2?style=for-the-badge" />
</p>

<p align="center">
  A responsive currency converter that fetches exchange rates through an external API and converts currencies instantly.
</p>

---

## 📌 About The Project

Currency Converter is a web application built using HTML, CSS, and Vanilla JavaScript. It allows users to convert an amount from one currency to another using exchange rate data fetched from the Frankfurter API.

Users can enter an amount, select their source and target currencies, and get the converted result. The application also displays country flags corresponding to the selected currencies.

This project helped me practice JavaScript API integration, asynchronous programming, DOM manipulation, and working with external data.

## ✨ Features

- 💱 **Currency Conversion:** Convert an amount between selected currencies.
- 🌍 **Multiple Currencies:** Choose from the currency codes included in the application.
- 🚩 **Country Flags:** Automatically updates flags when a currency is selected.
- 🔄 **Dynamic Dropdowns:** Currency options are generated using JavaScript.
- 🌐 **Exchange Rate API:** Fetches exchange rates from the Frankfurter API.
- 🔢 **Amount Validation:** Prevents amounts below 1 by setting the minimum amount to 1.
- 📱 **Responsive Design:** Adapts to desktop, tablet, and mobile screens.
- 🎨 **Modern UI:** Features a glass-style interface with a gradient background.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling, glass effect, and responsive layout |
| JavaScript | Conversion logic and DOM manipulation |
| Frankfurter API | Exchange rate data |
| FlagsAPI | Displaying country flags |
| Font Awesome | Icons |

## 🔌 API Integration

This project uses the **Frankfurter Exchange Rate API** to retrieve currency exchange rates.

API endpoint pattern:

```text
https://api.frankfurter.dev/v2/rate/{from}/{to}
```

The application fetches the selected currency pair's exchange rate and calculates the converted amount.

**Conversion formula:**

```text
Converted Amount = Entered Amount × Exchange Rate
```

## 🧠 Concepts I Practiced

- DOM manipulation
- JavaScript objects and loops
- Dynamic HTML element creation
- Event listeners
- `fetch()` API
- Async/Await
- Working with JSON responses
- API integration
- Template literals
- Conditional statements
- Input validation
- Updating image sources dynamically
- Responsive CSS media queries

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/uroojrizwan-sketch/Currency-Converter-.git
```

### 2. Open the Project Folder

```bash
cd Currency-Converter-
```

### 3. Open the Application

Navigate to the `Currency Converter` folder and open `index.html` in your browser.

No additional package installation is required.

**Note:** An internet connection is required to fetch exchange rates and load country flags from external services.

## 📂 Project Structure

```text
Currency-Converter-/
│
└── Currency Converter/
    │
    ├── index.html
    ├── style.css
    ├── codes.js
    └── index.js
```

## 🌱 What I Learned

Building this project improved my understanding of how JavaScript communicates with external APIs and uses the returned data to update a webpage.

I also gained practical experience with asynchronous JavaScript, dynamic dropdowns, event handling, and responsive CSS design.

## 🔮 Future Improvements

- Add a currency swap feature.
- Add loading indicators while fetching exchange rates.
- Improve API error handling.
- Display the last updated exchange rate information.
- Add a conversion history section.
- Improve accessibility and user feedback.

## 👩‍💻 Author

**Urooj Rizwan**

BS Computer Science Student | Frontend Developer

- GitHub: [@uroojrizwan-sketch](https://github.com/uroojrizwan-sketch)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/urooj-rizwan-93a158374/)

---

<p align="center">
  ⭐ If you like this project, consider giving it a star!
</p>

<p align="center">
  Made with ❤️ by Urooj Rizwan
</p>
