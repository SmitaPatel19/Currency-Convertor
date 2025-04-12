# 💱 Currency Converter App

A clean and efficient Flutter application for converting currencies in real-time using the OpenExchangeRates API. Supports both USD-to-any and any-to-any currency conversions with a responsive UI.

---

## ✨ Features

- 🔄 Convert from **USD to any currency**
- 🔁 Convert between **any two currencies**
- 🌍 Supports all available global currencies
- 🌐 Real-time exchange rates using [OpenExchangeRates](https://openexchangerates.org/)
- 📱 Simple and responsive interface

---

## 🧠 Project Structure

```
lib/
├── components/
│   ├── any_to_any_currency.dart
│   └── usd_to_any_currency.dart
├── functions/
│   └── fetch_functions.dart
├── models/
│   ├── allcurrencies_model.dart
│   └── rates_model.dart
├── screens/
│   └── home_screen.dart
├── utils/
│   └── api_key.dart
└── main.dart
```

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Flutter SDK
- Dart SDK
- Android Studio or VS Code with Flutter plugin

### 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SmitaPatel19/Currency-Convertor.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Currency-Convertor
   ```

3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Add your API key to:
   ```
   lib/utils/api_key.dart
   ```

5. Run the app:
   ```bash
   flutter run
   ```

---

## 📚 Dependencies

```yaml
dependencies:
  flutter:
  http: ^1.0.0
```

---

## 🤝 Contributing

Feel free to contribute by opening issues or submitting pull requests. All improvements are welcome!

---

Happy Coding! 💙