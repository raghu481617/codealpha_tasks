# 🏨 Hotel Reservation System

A simple console-based Java application for managing hotel room reservations. This project demonstrates core Object-Oriented Programming (OOP) concepts such as Abstraction, Polymorphism, Encapsulation, and Inheritance.

## ✅ Features

- 🛏 Book rooms in three categories: Luxury, Deluxe, and Super Deluxe
- 👥 Single or double occupancy options
- 💰 Adjustable room rates for each category
- 📶 Wi-Fi available in Deluxe and Super Deluxe rooms
- 🚗 Transportation and 🧺 Laundry services as optional add-ons
- 📊 View room status (occupied/vacant)
- ❌ Cancel reservations
- 🔄 Smart fallback: if chosen room is unavailable, system offers alternatives

## 🔧 How It Works

### 🧭 Menu Options:
- `b` ➤ Book a room
- `s` ➤ Avail a service
- `c` ➤ Cancel a booking
- `e` ➤ Exit system

### 📝 Booking Flow:
1. Enter name
2. Choose room type (Luxury, Deluxe, Super Deluxe)
3. Select occupancy (1/2)
4. Enter number of days
5. Get total fare & booking number
6. Optionally, add services (transport, laundry)

## 🚀 Getting Started

### 📦 Prerequisites
- Java JDK 8 or higher installed
- Code editor like VS Code or IntelliJ

### ▶️ Running the Project

Compile the Java files:
```
javac -d bin src/com/Hotel/Reservation/*.java
```

Run the program:
```
java -cp bin com.Hotel.Reservation.MainScreen
```

✅ No external dependencies or packages are required.

## 🛠️ Customization

You can enhance or modify:
- Room rates
- Room capacity
- Add database support for saving bookings
- Implement login system or GUI with JavaFX

## 📄 License

This project is intended for educational purposes only.  
Feel free to fork, improve, and share