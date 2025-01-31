
# SQLite Database Viewer

A simple web-based viewer for SQLite databases. This application allows users to load a `.sqlite` file, view the structure of tables, and display their data in a user-friendly interface. It provides features for navigating through the database tables, editing table data, and viewing the table structure (columns and data types).

## Features

-   **Load SQLite Databases**: Open `.sqlite` files directly from your browser or load them from a server URL.
-   **View Table Structure**: Display column names, data types, and constraints.
-   **View Table Data**: Browse through table rows and columns.
-   **Edit Data**: Edit the data in a table directly from the interface.
-   **Responsive Layout**: Flexible and responsive design that adapts to different screen sizes.

## Installation

This project does not require any server-side setup. To use it, simply clone or download the files and open the `index.html` file in a web browser.

### Steps:

1.  Clone or download the repository:

```bash
git clone https://github.com/Planetbiru/SQLite-Database-Viewer.git
```

2. Open the `index.html` file in your browser:

```bash
open index.html
```

## Usage

1.  **Load an SQLite File From Server**:
    
    -   Enter the URL of the SQLite database and click the **Load from Server** button in the main section to load the database from a server.
2.  **Load an SQLite File**:
    
    -   Click the **Choose File** button in the main section to upload an `.sqlite` file from your computer.
3.  **View Table List**:
    
    -   Once the database is loaded, all table names will appear in the sidebar on the left. Click on a table name to view its structure or data.
4.  **View Table Structure**:
    
    -   Click the `#` link next to a table name in the sidebar to view the table's structure (columns, data types, constraints).
5.  **View Table Data**:
    
    -   Click the table name in the sidebar to view its data. Data is displayed in a table format.
6.  **Edit Table Data**:
    
    -   Click on a row of data to select it. The corresponding data fields will appear in the right sidebar for editing.
    -   Modify the values as needed, and submit the changes.

## Technologies Used

-   **HTML5**: Markup language for the structure of the web page.
-   **CSS3**: Styling for the layout and design.
-   **JavaScript**: Interactivity, including loading the SQLite database, displaying data, and handling user input.
-   **SQL.js**: A JavaScript library to read and interact with SQLite databases in the browser.

## File Structure

```hash
- index.html # Main HTML file containing the app's structure
```

## Known Issues

-   Large SQLite databases may take time to load in the browser due to browser memory limitations.
-   Some browser-specific issues may arise with file handling.
-   CORS (Cross-Origin Resource Sharing) issues may prevent loading databases from some servers. Ensure that the server supports CORS or use a proxy if necessary.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome! If you encounter any bugs or have suggestions for improvements, please open an issue.
