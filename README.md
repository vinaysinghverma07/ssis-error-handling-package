# SSIS Error Handling Package

This SSIS package demonstrates how to implement error redirection when importing data from a TXT/SQL source. If a row fails due to datatype mismatch or data issues, it is redirected to a separate error table/files as configured for further review without failing the entire package.

## Features

- Data flow from csv source to SQL destination
- Error rows captured using red arrows (error output)
- Error data stored in a separate SQL table and text files.

## How to Use

1. Open the solution in Visual Studio with SSDT. I have utilised visual studio 2019 edition.
2. Update the connection strings as per your environment and files available.
3. Run the package.
