# 💱 Currency Converter

A simple and responsive web-based currency converter that uses real-time exchange rates to convert between different currencies, along with dynamic country flags.

## 🚀 Features

* Convert between multiple international currencies
* Real-time exchange rates using API
* Default conversion: USD → PKR
* Dynamic country flags based on selected currency
* Clean and responsive UI
* Input validation for amount

## 🛠️ Technologies Used

* HTML
* CSS
* JavaScript (Vanilla JS)
* Exchange Rate API

## 📁 Project Structure

```
├── index.html     # Main HTML file
├── style.css      # Styling
├── app.js         # Core logic for conversion
├── codes.js       # Currency and country code mapping (required)
```

## ⚙️ How It Works

1. User enters an amount
2. Selects "From" and "To" currencies
3. Clicks **Get Exchange Rate**
4. App fetches real-time data from API
5. Displays converted amount instantly

## 🌐 API Used

https://latest.currency-api.pages.dev/v1/currencies

## 📸 Example Output

```
1 USD = 278.50 PKR
```

* Flags update automatically based on selected currencies

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/currency-converter.git
```

2. Open `index.html` in your browser

> ⚠️ Make sure `codes.js` is included (contains currency-country mapping)

## 📌 Future Improvements

* Add search functionality in dropdown
* Add dark mode
* Add historical exchange rates graph
* Improve mobile responsiveness

## 🙌 Acknowledgment

* Exchange rate data provided by public API
* Flags provided by FlagsAPI
