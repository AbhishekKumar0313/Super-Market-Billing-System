# Super Market Billing System 🛒

A C++ console-based application designed for managing billing operations in a supermarket. This system allows users to add items, track inventory, and generate bills dynamically.

## Features ✨

- **Add Items**: Users can add items to the system with details like item name, rate, and quantity.
- **Generate Bills**: Users can generate bills based on items in stock and their quantities.
- **Update Inventory**: The system automatically updates item quantities as they are billed.

## Technologies Used 🛠️

- **C++**: Core programming language used for the application logic.
- **File Handling**: Utilized file I/O operations to store and update item data in text files.
- **Windows API**: Used for system operations such as clearing the console screen and pausing execution.

## Setup and Installation ⚙️

1. **Download the Source Code**:
   - Clone or download the repository containing the `super_market_billing.cpp` file.

2. **Compile the Code**:
   - Use a C++ compiler to compile the source code. For example:
     ```bash
     g++ -o super_market_billing super_market_billing.cpp
     ```

3. **Run the Application**:
   - Execute the compiled binary:
     ```bash
     ./super_market_billing
     ```

4. **File Path Configuration**:
   - Ensure that the file path used in the code (`D:/Bill.txt`) is correct and accessible. Modify the path if necessary.

## Usage 🚀

1. **Add Items**:
   - Choose the option to add items, then input the item name, rate, and quantity. The item will be saved to the `Bill.txt` file.

2. **Print Bill**:
   - Choose the option to print a bill, then input the item name and quantity. The application will read from the `Bill.txt` file, calculate the total amount, and update the item quantities.

3. **Close Session**:
   - Choose to close the session to finalize billing and calculate the total bill amount.

## Example Output 📋

```bash
Welcome To Super Market Billing System
**************************************
1. Add Item
2. Print Bill
3. Exit
Enter Choice: 1

Enter Item Name: Milk
Enter Rate Of Item: 50
Enter Quantity Of Item: 10
Item Added Successfully

Welcome To Super Market Billing System
**************************************
1. Add Item
2. Print Bill
3. Exit
Enter Choice: 2

Enter Item: Milk
Enter Quantity: 2

 Item | Rate | Quantity | Amount
 Milk   50     2         100
 Total Bill ----------------- : 100
 Thanks For Shopping!
