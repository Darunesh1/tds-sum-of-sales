# Sales Summary 2025

## Overview
This is a single-page web application designed to read sales data from an attached `data.csv` file. It calculates the total sum of the 'sales' column and displays this summary prominently on the page, with the title "Sales Summary 2025". The application utilizes Bootstrap 5 for styling.

## Features
*   Fetches and processes data from an attached `data.csv` file.
*   Calculates the sum of the 'sales' column.
*   Displays the total sales figure within a designated HTML element (`#total-sales`).
*   Sets the page title to "Sales Summary 2025".
*   Integrates Bootstrap 5 for a responsive and modern user interface.

## Usage
1.  Ensure the `data.csv` file is present in the project's attachments.
2.  Open the `index.html` file in your web browser.
3.  The application will automatically load, process the CSV, and display the total sales.

## Technical Details
The application is built using plain HTML, CSS, and JavaScript.
*   **HTML:** Provides the structure of the single-page application, including the element to display the total sales.
*   **JavaScript:** Handles the logic for fetching the `data.csv` file, parsing its content (assuming a comma-separated format), iterating through the rows to sum the 'sales' column, and updating the DOM with the calculated total.
*   **CSS:** Bootstrap 5 is loaded via CDN from `jsdelivr` to provide a clean and responsive design.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.