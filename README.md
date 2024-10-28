Here is a sample `README.md` for your project:

---

# Persediaan Barang (Inventory Management System)

This project is a simple inventory management system implemented in Java. It defines a product class (`barangJualan`) and an inventory class (`PersediaanBarang`) to manage and display the stock information of products in a specific location.

## Features

- **Product Information**: Allows you to input and display basic information about products, including name, price, discount price, and stock quantity.
- **Inventory Location**: Displays product availability by location.

## Project Structure

- `barangJualan`: A class representing individual products, their prices, and stock levels.
- `PersediaanBarang`: A class representing inventory at a specific location.
- `Main_app`: The main class to run the project.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine (version 8 or above).

### Running the Project

1. Clone the repository or download the `.java` files.
2. Open a terminal in the project directory.
3. Compile the code with the following command:
   ```bash
   javac Main_app.java
   ```
4. Run the code with the following command:
   ```bash
   java Main_app
   ```

### Expected Output

Upon running the program, you should see information about two products (e.g., `SADPHONE` and `HappyPhone`) displayed twice, along with the discount prices and stock levels at the specified location (`DEWA cell`).

### Sample Output
```
lokasi: DEWA cell
Nama Produk: SADPHONE
Harga: Rp1500000.0
Harag Diskon: Rp1350000.0
Persediaan: 999
Nama Produk: HappyPhone
Harga: Rp1500000.0
Harag Diskon: Rp2850000.0
Persediaan: 10
```

## Code Notes

- `barangJualan` calculates a discount price by applying a 10% discount on the first product and an incorrect 90% increase on the second.
- `PersediaanBarang` uses `barangJualan` as a parameter to print the product's stock information along with its location.

## Future Improvements

- **Error Fix**: Fix the calculation for `hargadiskon2` to apply the correct discount.
- **Dynamic Product List**: Allow for multiple products in a list rather than hardcoding two items.
- **Interactive Features**: Add user inputs for dynamic inventory control.

---

