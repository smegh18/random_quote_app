# Random Quote App

A simple Flutter app that fetches and displays random quotes from the **Quotable API**.

## 📱 Features
- Fetches a random quote from `https://api.quotable.io/random`
- Displays the quote in a clean and minimal UI
- Refreshes with a new quote when the **Fetch Quote** button is pressed

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- Flutter SDK
- Dart
- Android Studio or VS Code

### Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/random-quote-app.git
   cd random-quote-app
   ```

2. **Install dependencies**
   ```sh
   flutter pub get
   ```

3. **Run the app**
   ```sh
   flutter run
   ```

## 🛠️ How It Works

1. The UI consists of a `Text` widget displaying the quote and a `Fetch Quote` button.
2. When the button is pressed, the `fetchQuote()` function is called.
3. The function makes an HTTP GET request to `https://api.quotable.io/random`.
4. The response is decoded to extract the quote (`content` field).
5. The `setState()` method updates the UI with the new quote.



