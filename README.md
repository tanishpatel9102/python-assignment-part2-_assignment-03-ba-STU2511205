🍽️ Restaurant Order System (Python Assignment)
👀 What this project is about

This is a small Python project where I tried to simulate a restaurant ordering system.

It handles things like:

Menu display
Adding/removing items from cart
Order billing
Inventory tracking
Sales analysis

Basically, it combines multiple Python concepts into one mini real-world example.

⚙️ What it can do
📋 Menu handling
Displays items category-wise (Starters, Mains, Desserts)
Shows price and availability
Finds:
Total items
Available items
Most expensive item
Items under ₹150
🛒 Cart system
Add items to cart
Remove items
Update quantity
Prevents:
Adding unavailable items
Adding items not in menu

Also shows cart state after each operation (so it's easy to track what's happening).

💵 Billing system
Calculates subtotal
Adds GST (5%)
Shows final total in a clean format
📦 Inventory management
Uses deep copy to safely backup inventory
Updates stock after orders
Gives reorder alerts when stock is low
📊 Sales analysis
Calculates revenue per day
Finds best-selling day
Finds most ordered item
Adds new sales data and recalculates everything
Prints all orders in a readable format
▶️ How to run

Just run:

python part2_order_system.py

Make sure Python is installed.

📁 Project structure
python-assignment-part1/
│
├── part2_order_system.py
└── README.md
💭 What I learned
How to manage structured data (dicts inside dicts)
Writing reusable functions (cart system)
Handling edge cases (invalid items, unavailable stock)
Working with loops and conditions in real scenarios
Basic inventory and sales logic
⚠️ Some things to note
Cart operations are hardcoded (not user input based)
There was a duplicate function earlier, but final version uses the correct one
Output is printed step-by-step for better understanding (not optimized for production)

👨‍💻 Author

Tanish Patel

