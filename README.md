## World Clock

This project is a web application that displays the current time in different cities around the world. It also allows users to select a city from a dropdown menu and display the current date and time for that city, updating every second. The application is styled with custom fonts and includes a beautiful background image inspired by Studio Ghibli.

### Features

- Display the current time for Los Angeles and Paris.
- Select a city from a dropdown menu to display its current time.
- Automatically updates the time every second for the selected city.
- Beautifully styled with custom fonts and a background image.

### Technologies Used

- **HTML5**: Structure of the web application.
- **CSS3**: Styling of the web application.
- **JavaScript**: Dynamic behavior and time updates.
- **Moment.js**: Handling date and time.
- **Moment Timezone**: Handling different timezones.
- **Ionicons**: Icons used in the project.
- **Google Fonts**: Custom fonts for styling.

### Setup

1. Clone the repository from GitHub:
   ```bash
   git clone https://github.com/TracyK10/world-clock.git
   ```

2. Navigate to the project directory:
   ```bash
   cd world-clock
   ```

3. Open the `index.html` file in your web browser to view the application.

### Usage

1. Open the web application in your browser.
2. The current time for Los Angeles and Paris will be displayed automatically.
3. Use the dropdown menu to select a different city. The current date and time for the selected city will be displayed and updated every second.
4. Click the "Go Back" link to return to the previous page.

### Project Structure

```
world-clock/
├── css/
│   └── styles.css
├── javascript/
│   └── script.js
└── index.html
```

- `index.html`: The main HTML file that structures the web page.
- `css/styles.css`: The CSS file that styles the web page.
- `javascript/script.js`: The JavaScript file that contains the logic for updating the time and handling city selection.

### Customization

You can customize the project by adding more cities to the dropdown menu. To do this, add more `<option>` elements with the appropriate timezone values in the `index.html` file.

```html
<option value="Asia/Tokyo">Tokyo</option>
<option value="Australia/Sydney">Sydney</option>
```

### Live Demo

You can view a live demo of the project [here](https://karanjatracy-world-clock.netlify.app/).

### Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue on GitHub.

### License

This project is open-sourced and licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgements

- This project was coded by Tracy Karanja.
- Special thanks to the creators of Moment.js, Moment Timezone, Ionicons, and Google Fonts.

Feel free to check the source code on [GitHub](https://github.com/TracyK10/world-clock) and star the repository if you find it useful!