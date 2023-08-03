# TimeKeeper
![image](https://github.com/bdinyarian/TimeKeeper/assets/21012337/09d08b33-9988-4721-81cb-8a5ebabfd9d3)

TimeKeeper is a web-based application for tracking time spent on projects. It allows users to add projects, start and stop timers for each project, and export and import project data in CSV format. The application uses HTML, CSS, and JavaScript to provide a simple and intuitive user interface.

## Developer Information

- Developer: Bahram Dinyarian
- Email: bahramdinyarian@gmail.com

## Getting Started

To use TimeKeeper, simply open the `index.html` file in a web browser. The application will load the saved project data from the browser's localStorage and display it in a table. Users can add new projects, start and stop timers, and export and import project data using the buttons provided.

## Usage

### Adding a Project

1. Click the "Add Project" button at the bottom of the page.
2. Enter the project name and description in the corresponding input fields.
3. Click the "Start" button to start the timer for the project.
4. Click the "Stop" button to stop the timer for the project.

### Deleting a Project

1. Find the project you want to delete in the table.
2. Click the "Delete" button next to the project.
3. The project will be removed from the table and its data will be deleted from localStorage.

### Exporting Project Data

1. Click the "Export" button at the bottom of the page.
2. A CSV file named "TimeKeeper.csv" will be downloaded, containing the project data.

### Importing Project Data

1. Prepare a CSV file with the following format: `Record #, Project Name, Project Description, Time Elapsed, Date`.
2. Click the "Import" button at the bottom of the page.
3. Select the CSV file you want to import.
4. The data from the CSV file will be added to the table and saved in localStorage.

### Resetting the Data

1. Click the "Reset" button at the bottom of the page.
2. Confirm the action when prompted.
3. All data will be removed from the table and localStorage.

### Dark Mode

- To enable dark mode, click the "Dark Mode" toggle button at the bottom of the page.
- To disable dark mode, click the toggle button again.

## Licensing

This program is licensed under the GNU General Public License (GPL) version 3 or later. You can redistribute and modify the code under the terms of this license. For more details, please refer to the [GNU General Public License](https://www.gnu.org/licenses/).

**Note:** This program comes with ABSOLUTELY NO WARRANTY.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## Acknowledgments

Special thanks to Bahram Dinyarian for developing this TimeKeeper web application.
