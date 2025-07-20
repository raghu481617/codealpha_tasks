# Stock Trading Platform

Welcome to the Stock Trading Platform application repository. This desktop application allows users to simulate stock trading using real-time data from Yahoo Finance. You can buy and sell stocks, manage a virtual portfolio, and analyze your trading performance—all in a safe, risk-free environment. Perfect for beginners learning about the stock market or experienced traders testing strategies.

## 🔧 Features

- Real-time stock data from Yahoo Finance
- Simulated buying and selling of stocks
- Portfolio management and visualization
- Profit and loss tracking
- Virtual wallet for managing funds
- User-friendly interface built with JavaFX

## 🚀 Getting Started

### 📋 Prerequisites

- Java Development Kit (JDK) 11 or above (JDK 21 recommended)
- JavaFX SDK (download from [GluonHQ](https://gluonhq.com/products/javafx/))

### 💻 Installation & Running

1. **Clone the repository:**
   ```bash
   git clone https://github.com/BommisettyRaghu/Stock-Trading-Platform.git
   cd Stock-Trading-Platform
   ```

2. **Download and extract JavaFX SDK:**
   - Download from [GluonHQ](https://gluonhq.com/products/javafx/)
   - Extract to: `C:\javafx-sdk-21.0.8` (or your preferred location)

3. **Compile the project:**
   ```bash
   javac --module-path "C:\javafx-sdk-21.0.8\lib" --add-modules javafx.controls,javafx.fxml -d out java/com/example/homework10/*.java
   ```

4. **Run the application:**
   ```bash
   java --module-path "C:\javafx-sdk-21.0.8\lib" --add-modules javafx.controls,javafx.fxml -cp out com.example.homework10.GUI
   ```

## 📘 Usage

- **Login/Sign Up:** Create an account or log in to start.
- **Search Stocks:** Enter a stock symbol (e.g., `AAPL`, `GOOG`), select a date range, and view price data.
- **Buy/Sell:** Enter share count to buy or sell stocks.
- **Portfolio:** View your holdings, transaction history, and profit/loss.
- **Wallet:** Deposit or withdraw virtual funds.

## 📄 License

This project is for educational purposes only.