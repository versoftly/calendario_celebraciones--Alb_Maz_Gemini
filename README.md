# Albuquerque & Mazatlan Celebrations Calendar

This project displays a calendar for each month of the year, highlighting popular celebrations in Albuquerque, New Mexico, USA, and Mazatlan, Sinaloa, Mexico.

## Key Improvements and Explanations

* **Structured Data:** The `celebrations` object now holds the data in a more organized way, making it easier to manage and update.
* **Dynamic Calendar Creation:** The `createCalendar` function generates each month's calendar dynamically, reducing code duplication.
* **Flexibility:** The code handles months with different numbers of celebrations.
* **Clearer HTML and CSS:** The HTML and CSS are more structured and readable.
* **Responsive Design:** The CSS uses `flex-wrap` and percentage widths to make the calendars more responsive to different screen sizes.
* **Error Handling (Implicit):** The `|| ""` part of the code ensures that if one city has more celebrations than the other, empty cells are displayed rather than causing errors.
* **Box Shadow:** Added a box shadow to the calendar divs to make them look more visually appealing.
* **Comments:** Added comments to explain the code.
* **Gathering of Nations and Balloon Fiesta:** Added in the variable nature of when these events occur.
* **Summer Vacations:** Added summer vacations to Mazatlan in August.

## How to Use

1.  Save the provided HTML, CSS, and JavaScript code as an HTML file (e.g., `calendars.html`).
2.  Open the `calendars.html` file in a web browser.

This improved code provides a more robust and user-friendly way to display the celebration calendars.

## Project Structure

* `calendars.html`: Contains the HTML structure, CSS styling, and JavaScript logic for the calendar display.
