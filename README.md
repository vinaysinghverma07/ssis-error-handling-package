# SSIS Error Handling Package

This SSIS package demonstrates how to implement **error handling in data flow tasks** using SQL Server Integration Services (SSIS). It captures bad or incorrectly typed data from a source and redirects it to an error output for further inspection or correction.

---

## 📁 Project Structure

| File/Folder | Description |
|-------------|-------------|
| `error-handling-in-ssis.sln` | Visual Studio Solution file |
| `error-handling-in-ssis.dtproj` | SSIS Project file |
| `error-handling-in-ssis.dtsx` | Main SSIS Package (Control and Data Flow logic) |
| `SampleInput.csv` | Sample input file used for testing (optional) |
| `images/` | Screenshots of control flow and data flow |

---

## 🛠️ Features

- Reads data from SQL Server or CSV/
- Redirects rows with data-type conversion or constraint errors to error output file.
- Writes clean data to destination table or file.
- Logs errors for review.

---

## 🚀 How to Use -

### 📌 Prerequisites

- SQL Server Data Tools (SSDT).
- Visual Studio 2015 or above (with SSIS).
- SQL Server (any version 2012+), in my case it is 2008r2.
- Sample database with intended table (if using SQL source).

### 🧩 Steps to Run the Package

1. Clone or download this repository:
   ```bash
   git clone https://github.com/vinaysinghverma07/ssis-error-handling-package.git
   
## Notes

- This project is meant for educational purposes only. 
- Make sure your source files, database connection strings and file paths are configured before running the package.
- Please make sure to replace the "replace_your_system_name", "replace_your_sql_server_name" value with the appropriate values of your system/computer and sql server name.
