# ✈️ FlightAutoBot – UiPath Flight Tracking Automation

This project automates the process of searching for flights based on user inputs such as source, destination, and travel date. It retrieves relevant flight details, stores the data in an Excel file, and sends the file to the user via email. The automation includes logging and exception handling to ensure robust and seamless execution.

---

## ⚙️ Features

- ✅ Automated flight search from user input
- 📤 Excel export of retrieved flight details
- 📧 Email notification with Excel attachment
- 🧠 Built-in logging and exception handling
- 🧩 Modular workflows for better scalability

---

## 🧰 Dependencies

The project uses the following UiPath packages:

| Package                      | Version          |
|-----------------------------|------------------|
| UiPath.Excel.Activities     | 2.25.1-preview   |
| UiPath.Mail.Activities      | 2.0.11           |
| UiPath.System.Activities    | 25.2.1           |
| UiPath.UIAutomation.Activities | 25.2.1-preview |

Make sure to install these dependencies in your UiPath Studio before running the project.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/Smohanta23/Flight-Finder-RPA.git]
Then navigate to "ExtractDataFromWeb.xaml" and Main.xaml" files for main workflow sequences.
