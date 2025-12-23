# Pizza Siparis Sistemi

A simple pizza ordering notebook that uses a menu + decorator pattern to build a pizza, calculate price, and save the order to a CSV file.

## Features
- Generates a `Menu.txt` file at runtime
- Lets the user pick a pizza base and a sauce
- Calculates total cost
- Collects customer info
- Appends orders to `Orders_Database.csv`

## Files
- `Pizza_Sipariş_Sistemi.ipynb` - Main notebook
- `Menu.txt` - Generated menu (created when you run the notebook)
- `Orders_Database.csv` - Order log (created/appended at runtime)

## How to run
Option 1: Jupyter (recommended)

```powershell
jupyter notebook "Pizza_Sipariş_Sistemi.ipynb"
```

Option 2: Google Colab
- Upload `Pizza_Sipariş_Sistemi.ipynb` to Colab and run all cells.

## Orders_Database.csv columns
Each row has:

```
name, tc, cc_num, cc_cvv, timestamp, total_cost, description
```

## Notes
- The notebook expects interactive input (menu selection and customer info).
- Output files are created in the same folder as the notebook.

