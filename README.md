🧾 OutriX Tasks - Invoice Generator

A Python-based software to create professional invoices for products and services with auto-calculated taxes and totals.
The project provides a clean interface where users can enter product/service details and export invoices as PDF files.

🚀 Features

Add multiple products/services with name, quantity, and price

Automatic tax calculation

Auto total calculation (subtotal + tax = grand total)

Export invoices as PDF

Simple and user-friendly interface

🛠️ Technologies Used

Python 3

Tkinter → For GUI

docxtpl / reportlab → For generating invoice templates and PDF export

📂 Project Structure
Invoice_Generator/
│-- main.py           # Main Python script
│-- templates/        # Invoice templates
│-- output/           # Generated invoices
│-- README.md         # Project documentation

▶️ How to Run

1. Clone the repository:

git clone https://github.com/Namanverma21/OutriX_tasks_Invoice_Generator.git

2. Navigate to project folder:

cd OutriX_tasks_Invoice_Generator

3. Install required libraries:

pip install -r requirements.txt

4. Run the application:

python main.py

📑 Sample Invoice

An example generated invoice looks like this:

Invoice Number: 1001
Customer Name: John Doe
---------------------------------
Item          Qty   Price   Total
Product A     2     500     1000
Product B     1     300      300
---------------------------------
Subtotal: 1300
Tax (18%): 234
Grand Total: 1534
