# ☕ Coffee Machine Simulator

Welcome to the **Coffee Machine Simulator** – a Python-based command-line application that lets you brew your favorite drinks like a barista! Choose from **Espresso**, **Latte**, or **Cappuccino** and watch how the machine handles resources, payments, and preparation in real-time.

---

## 🚀 Features

- 🧮 Coin-based payment system  
- 📦 Resource management (water, milk, coffee)  
- 🔐 Change calculator and refund if not enough money  
- 📊 Command to check current machine resources  
- 📴 Exit command to turn off the machine  

---

## 🛠️ How It Works

1. User selects a drink (`espresso`, `latte`, or `cappuccino`)
2. The machine checks if there are enough ingredients
3. User inserts coins (quarters, dimes, nickels, pennies)
4. Payment is validated and change is returned if necessary
5. The drink is prepared and resources are deducted
6. The cycle continues until the user types `off`

---

## 💻 Code Structure

All logic is inside a single Python script:

### `main.py` (or `Coffee_Machine.py` / `Drink_Machine.py`):

- `MENU`: Dictionary with recipes and costs  
- `resources`: Tracks current stock of ingredients  
- `is_resource_sufficient()`: Checks ingredient availability  
- `process_coins()`: Simulates coin input  
- `is_transaction_successful()`: Handles money logic  
- `make_coffee()`: Updates inventory and prints confirmation  
- `while` loop: Main interface for drink selection, reports, and machine control  

---

## 🧪 Sample Run


---

## 🧰 Requirements

- Python 3.x  
- No external libraries required  

---

## 🧠 Author

**Hare Krishna Mishra**  
Python Developer | Data Enthusiast | Web Creator  
📫 Reach out on GitHub or LinkedIn  

---


