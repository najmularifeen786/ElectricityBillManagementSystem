# ⚡ Electricity Bill Management System

A **JavaFX-based desktop application** that automates electricity billing operations — from bill generation and discount management to payment tracking and revenue analysis.

---

## 📽️ Demo Video

> Watch the full project walkthrough:

**[▶ Click here to watch the demo](https://youtu.be/zxUaX5SdKQc)**

---

## 📥 Download

### Windows Executable (No Installation Required)

Download the latest packaged Windows application directly — no Java or Maven installation needed:

**[⬇ Download Latest Release](https://github.com/najmularifeen786/ElectricityBillManagementSystem/releases)**

### Quick Start

1. Download the latest `.zip` release.
2. Extract the archive to any folder.
3. Make sure `billsdata.txt` is in the **same folder** as `ElectricityBillManagementSystem.exe`.
4. Double-click `ElectricityBillManagementSystem.exe` to launch.

> **Note:** The executable is self-contained. No Java installation is required.

---

## ✨ Features

| Feature | Status |
|---|---|
| Bill Generation (CNIC, name, address, category, meter readings) | ✅ Available |
| Dynamic Discounts | ✅ Available |
| Customizable Tax Rates | ✅ Available |
| Bill Payment Processing & Status Tracking | ✅ Available |
| Bill Search | ✅ Available |
| File-Based Data Storage (`billsdata.txt`) | ✅ Available |
| Apply Late Payment Fine | 🔧 Coming Soon |
| Overall Revenue Statistics | 🔧 Coming Soon |

> **Note on Coming Soon features:** The *Apply Late Payment Fine* and *Overall Revenue Statistics* modules are functional when the project is compiled and run from source locally. Packaging support for these features in the Windows executable is currently in progress.

---

## 📸 Screenshots

<table>
  <tr>
    <td align="center"><strong>Main Menu</strong><br><img src="src/screenshots/mainmenu.png" width="340"></td>
    <td align="center"><strong>Generate Bill</strong><br><img src="src/screenshots/generatebill.png" width="340"></td>
  </tr>
  <tr>
    <td align="center"><strong>Apply Discount</strong><br><img src="src/screenshots/applydiscount.png" width="340"></td>
    <td align="center"><strong>Pay Bill</strong><br><img src="src/screenshots/paybill.png" width="340"></td>
  </tr>
  <tr>
    <td align="center"><strong>Update Taxes</strong><br><img src="src/screenshots/taxes.png" width="340"></td>
    <td align="center"><strong>Apply Late Fine</strong><br><img src="src/screenshots/fine.png" width="340"></td>
  </tr>
  <tr>
    <td align="center" colspan="2"><strong>Revenue Statistics</strong><br><img src="src/screenshots/revenue.png" width="500"></td>
  </tr>
</table>

---

## 🛠️ Technologies Used

- **Language:** Java 23
- **Framework:** JavaFX
- **Styling:** JavaFX CSS
- **Build Tool:** Maven
- **Data Storage:** File-based (`billsdata.txt`)
- **OOP Concepts:** Encapsulation, Association, Inheritance, Enumeration

---

## 🚀 Running from Source

> Only needed if you want to explore or modify the code. For regular use, download the executable above.

### Requirements

- Java JDK 23 or later
- Maven

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/najmularifeen786/ElectricityBillManagementSystem.git
   cd ElectrictyBillManagementSystem
   ```

2. **Build and run**
   ```bash
   mvn clean javafx:run
   ```

> All features, including *Apply Late Payment Fine* and *Revenue Statistics*, are fully functional when running from source.

---

## 📦 Project Structure

```
ElectrictyBillManagementSystem/
├── src/
│   ├── main/
│   │   ├── java/com/example/demo4/
│   │   │   ├── ApplyDiscountController.java
│   │   │   ├── ApplyLateFineController.java
│   │   │   ├── CallGenerateBill.java
│   │   │   ├── Category.java
│   │   │   ├── Discount.java
│   │   │   ├── ElectricityBillSystem.java
│   │   │   ├── Fine.java
│   │   │   ├── GenerateBill.java
│   │   │   ├── GenerateBillController.java
│   │   │   ├── HelloApplication.java
│   │   │   ├── HelloController.java
│   │   │   ├── PayBillController.java
│   │   │   ├── Payment.java
│   │   │   ├── RevenueStatisticsController.java
│   │   │   ├── Taxes.java
│   │   │   └── TaxesController.java
│   │   └── module-info.java
│   └── resources/               # FXML files and UI resources
├── screenshots/
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md
```

---

## 📋 Release Information

### Version 1.0

- ✅ Bill Generation
- ✅ Bill Search
- ✅ Bill Payment Processing
- ✅ Discount Management
- ✅ Tax Management
- ✅ JavaFX Desktop Interface
- ✅ File-Based Data Storage
- ✅ Windows Executable Distribution
- 🔧 Late Payment Fine *(coming in next release)*
- 🔧 Revenue Statistics *(coming in next release)*

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your message"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request with a clear description of your changes.

Please ensure your code follows the existing style and structure.

---

## 📬 Contact

- **Author:** Najmul Arifeen
- **GitHub:** [github.com/najmularifeen786](https://github.com/najmularifeen786)
