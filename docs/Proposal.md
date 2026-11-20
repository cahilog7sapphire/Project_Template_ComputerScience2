# Smart Pantry Inventory and Expiration Tracker

## Summary
Smart Pantry Inventory and Expiration Tracker is a single-file, console-based application that allows the user to keep track of food items in the kitchen. Food items in the user’s pantry can be easily added and stored into a list (array) in Python in order to make the application very simple to run.

---

## Problem


---

## Features
1. **View items in pantry.**
   This will loop through the internal pantry list (array) and allow you to view all food items, quantities, and expiry dates.
2. **Add item to list.**
   User can add an item to their grocery list. It will be appended to the pantry list.
3. **Remove / consume item.**
   User can remove items from the pantry list once they have eaten them or thrown them away.
4. **View expiring items.**
   Using the `datetime` module, users can view what items are expiring in the next 3 days (or have expired).
5. **View low quantity items.**
   Users can filter the list to show items with only 1 quantity remaining. This means users know what items to purchase.

---

## Data Storage
Data is stored using a list (array) made up of dictionaries.

| Attribute | Data Type | Example |
| :--- | :--- | :--- |
| `item` | String | `"Fresh Milk"` |
| `storage` | String | `"Fridge"` |
| `quantity` | Integer | `1` |
| `expiry_date` | String | `"2026-11-23"` |

---

## Wireframe
Main Menu:
```text
==================================================
   SMART PANTRY INVENTORY & EXPIRATION TRACKER
==================================================
1. View All Items
2. Add New Item
3. Remove / Use Item
4. Check Expiring Soon
5. View Low-Stock List
0. Exit
==================================================
Choose an option: 4
