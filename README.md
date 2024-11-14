# Random Name Picker with Input Management

This web application allows users to randomly select a name from a list of names provided by the user. It also provides an option to generate a random number within a specified range. The user can add or remove input fields to enter multiple names, and the application ensures the list is valid before selecting a name.

## Features

- **Dynamic Name Input**: Add or remove name input fields dynamically with `+` and `-` buttons.
- **Validations**: The application ensures input is valid before proceeding, including:
  - Name fields must not be empty.
  - The minimum and maximum values for random number generation must be valid.
- **Random Selection**: Choose a random name from the list along with a random number within a defined range.
- **User-friendly Interface**: Easy-to-use and visually appealing UI with clear buttons for actions.

## Requirements

To use this application, you need the following:
- A modern web browser (Chrome, Firefox, Safari, etc.)
- Basic JavaScript enabled in your browser.

## How to Use

1. **Enter Minimum and Maximum Values**: Use the input fields at the top to specify the range for the random number generator.
2. **Add Names**: Click the `+` button to add a name input field. Enter a name in the text box.
3. **Remove Names**: Click the `-` button next to any name field to remove it.
4. **Random Selection**: Once you have entered the names and range, click the `TANLASH` button to randomly select a name and a number.

## How It Works

- **Adding Names**: Click the `+` button next to the name input to add another input field. If a name input is empty, the `+` button won't work.
- **Removing Names**: You can remove any name input by clicking the `-` button. At least one name input must remain.
- **Random Name Selection**: After adding names and specifying the minimum and maximum numbers, the system will randomly choose one name and a number between the specified range.

## Code Overview

- **HTML Structure**: Contains the main UI elements for the name inputs, random number range, and result display.
- **CSS Styling**: Provides a simple and responsive design with a focus on user experience.
- **JavaScript Functionality**:
  - Handles dynamic input creation and deletion.
  - Ensures that only valid data is processed.
  - Selects a random name and number and displays it in the result area.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This application was built using basic HTML, CSS, and JavaScript.
- Special thanks to the web development community for providing the resources and tutorials that helped in building this project.

