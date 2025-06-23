# GROUP C: SUPERMARKET DATABASE

The project website access [Supermarket database](https://kenjin32icon.github.io/Database-design-and-construction-/)

## Overview

This repository provides guidance and tools to the group C; SuperMarket Database project. The original database was made in LibreOffice, and this repo helps to bridge LibreOffice Base databases and Microsoft Access. If you use LibreOffice Base for database creation and want to leverage Access for advanced querying or integration, this project shows how to open LibreOffice `.odb` files within Access.

---

## Installation

To download the Supermarket Database project, click the link below:

[📥 Download the Supermarket Database Project](https://github.com/Kenjin32icon/Database-design-and-construction-/archive/refs/heads/main.zip)

To access the Access database file, click the link below:

[📁 Access Database File](https://github.com/Kenjin32icon/Database-design-and-construction-/blob/bc27087f15cd2e592ef42eedbdd0510cf361daf8/Database/Supermarket%20Database.accdb)

To access the LibreOffice Base database file, click the link below:

[📁 LibreOffice Base database file ](https://github.com/Kenjin32icon/Database-design-and-construction-/blob/bc27087f15cd2e592ef42eedbdd0510cf361daf8/The%20Supermarket%20database/The%20Supermarket%20Databse.odb)

---

## Contributors

- **Lewis**: Database Designer. AIIM/00477/2021
- **Joseph Kimani**: Project Leader. AIIM/01073/2021
- **Nesta Sila**: Chief Data Engineer. AIIM/01873/2021

---

## How to Download and Open the Database in Microsoft Access

Follow these simple steps to download and open the database in Microsoft Access:

1. **Download the Database Project**  
   - Click on the link to download the Supermarket Database Project: [📥 Download the Supermarket Database Project](https://github.com/Kenjin32icon/Database-design-and-construction-/archive/refs/heads/main.zip).
   - Extract the downloaded ZIP file to a location on your computer.

2. **Access the Access Database File**  
   - Click on the link to download the Access database file: [📁 Access Database File](https://github.com/Kenjin32icon/Database-design-and-construction-/path/to/your/access/database.accdb).
   - Save the file to your desired location.

3. **Open Microsoft Access**  
   - Launch Microsoft Access on your computer.

4. **Open the Database File**  
   - In Access, click on "File" in the top left corner.
   - Select "Open" from the menu.
   - Browse to the location where you saved the Access database file (`.accdb`).
   - Select the file and click "Open."

5. **Start Working with the Database**  
   - You can now view and manipulate the data within Microsoft Access.

---

## How to Open a LibreOffice Base Database in MS Access

Microsoft Access cannot open `.odb` files directly because they are LibreOffice native database containers. However, you can follow this method to access your data:

1. **Extract the Embedded Database**  
   LibreOffice Base files commonly use HSQLDB or Firebird as the backend, which is embedded inside the `.odb` container. To extract the data:  
   - Open the `.odb` file using LibreOffice Base.  
   - Export the database tables to a compatible format (such as CSV or an Access-supported database format).

2. **Import Data into Microsoft Access**  
   Using Access:  
   - Create a new database or open an existing one in Access.  
   - Use the import wizard to bring in the exported CSV or compatible database tables.  
   - Map the fields as needed and save the imported tables.

3. **Alternative: Connect via ODBC**  
   If your LibreOffice Base file connects to an external database (e.g., MySQL, PostgreSQL), configure an ODBC connection in Access to that external database for real-time querying without exporting.

---

## Additional Tips

- Keep your LibreOffice Base and Access versions updated for best compatibility.
- When exporting data, ensure the character encoding and data types are preserved to avoid data inconsistencies.
- Automate export and import processes with scripts if you need repeated synchronization.

--- 

Feel free to replace the placeholder link for the Access database file with the actual path to your file in the repository. Let me know if you need any more changes!
