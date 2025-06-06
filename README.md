# GROUP C:- SUPERMARKET DATABASE
## Overview

This repository provides guidance and tools to the group C; SuperMarket Database project.
For the original database was made in Libre Office this repo helps to bridges LibreOffice Base databases and Microsoft Access. If you use LibreOffice Base for database creation and want to leverage Access for advanced querying or integration, this project shows how to open LibreOffice `.odb` files within Access.

---
## Installation

To download the Supermarket Database project, click the link below:

[📥 Download the Supermarket Database Project](https://github.com/Kenjin32icon/Database-design-and-construction-/archive/refs/heads/main.zip)

## Contributors

- **Lewis**: Database Designer. AIIM/00477/2021
- **Joseph Kimani**: Project Leader. AIIM/01073/2021
- **Nesta Sila**: Chief Data Engineer. AIIM/01873/2021

---

## Requirements

To successfully use this repository, you need to have the following installed:

- **LibreOffice**:  
  LibreOffice is required since `.odb` files are native to LibreOffice Base. Installation can be found at [https://www.libreoffice.org/download/download/](https://www.libreoffice.org/download/download/)

- **Microsoft Access**:  
  Access will be used to open and work with LibreOffice Base files after conversion or linking.

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
