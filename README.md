# 📞 Calley Automation Testing Project

This project automates the full setup of a Calley Team Account using **Java**, **Selenium WebDriver**, **TestNG**, and the **Page Object Model** (POM) design pattern. It's part of a machine test for an Automation Testing Internship.

---

## 🚀 Features Covered

- ✅ User Registration with Calley Teams plan
- ✅ Login functionality
- ✅ Agent creation
- ✅ CSV list upload and mapping

---

## 🧰 Tech Stack

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)
- Data-Driven Testing (CSV / Excel)
- Git + GitHub

---

## 🗂 Project Structure

```
CalleyAutomation/
├── pom.xml
├── testng.xml
├── data/
│   └── sample.csv
├── src/
│   ├── main/java/
│   │   ├── config/             # Configurations
│   │   ├── pages/              # Page Object Model Classes
│   │   └── utils/              # Base Test, Config Reader, Excel Utils
│   └── test/java/tests/        # Test Classes
```

---

## ⚙️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/CalleyAutomation.git
   cd CalleyAutomation
   ```

2. Open in your IDE (Eclipse/IntelliJ)

3. Run tests using:
   ```bash
   mvn test
   ```

   Or directly run `testng.xml` in your IDE.


