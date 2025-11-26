# 💱 Currency Converter

![License](https://img.shields.io/github/license/Akhil9982/currency_converter?style=flat-square)
![Language](https://img.shields.io/github/languages/top/Akhil9982/currency_converter?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/Akhil9982/currency_converter?style=flat-square)

A simple and efficient web-based **Currency Converter** application. This tool allows users to convert amounts between different world currencies in real-time using live exchange rate data.

---

## 🌟 Live Demo

> https://akhil9982.github.io/currency_converter/

> <img width="514" height="546" alt="image" src="https://github.com/user-attachments/assets/162a02fa-4e96-4f0e-af15-57a79f40dda6" />

---

## 🚀 Features

- **Real-time Conversion**: Fetches the latest exchange rates to ensure accuracy.
- **Wide Currency Support**: Supports a vast array of global currencies (managed via `code.js`).
- **User-Friendly Interface**: Clean and intuitive design for quick conversions.
- **Responsive Design**: Works seamlessly on desktops, tablets, and mobile devices.
- **Flag Integration**: Displays country flags corresponding to the selected currency for better UX.

## 🛠️ Technologies Used

- **HTML5**: For the application structure.
- **CSS3**: For styling and layout (`styles.css`).
- **JavaScript**: For fetching API data and handling conversion logic (`app.js`).
- **Exchange API**: Utilizes a third-party API for fetching real-time exchange rates.

## 📂 Project Structure

```bash
currency_converter/
├── app.js           # Main application logic (API calls, UI updates)
├── code.js          # Contains country/currency codes and mapping
├── index.html       # Main HTML structure

💻 Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
You need a modern web browser (Chrome, Firefox, Safari, Edge) to run the application.

Installation

Clone the repository:

Bash

git clone [https://github.com/Akhil9982/currency_converter.git](https://github.com/Akhil9982/currency_converter.git)

Navigate to the project directory:

Bash

cd currency_converter

Run the App:

Simply double-click the index.html file to open it in your default browser.

OR, if you use VS Code, you can use the Live Server extension.

⚠️ API Configuration (Important)

If the app relies on a specific API key (e.g., from ExchangeRate-API or Open Exchange Rates) and it stops working, you may need to:

Open app.js.

Locate the API URL variable.

Replace the endpoint or add your own free API key if the public one has exceeded its limit.

🤝 Contributing

Contributions are welcome! If you'd like to improve the UI or add new features (like historical charts), feel free to fork the repo.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📜 License

Distributed under the GPL-3.0 License. See LICENSE for more information.

👤 Author

Akhil9982

GitHub: @Akhil9982

Made with ❤️ and JavaScript.
├── styles.css       # Stylesheet for the application
├── LICENSE          # GPL-3.0 License
└── README.md        # Project documentation
