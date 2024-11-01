# Aliza Fitness Website 

This project is part of the Aliza Fitness website, featuring a countdown timer that informs users about upcoming events or promotions. The timer counts down to a specified date and time, updating every second, and displays the remaining time in days, hours, minutes, and seconds. Once the countdown reaches zero, it shows "EXPIRED."

## Features

- Real-time countdown to a specific event or promotion.
- Displays time remaining in a user-friendly format: days, hours, minutes, and seconds.
- Automatic update every second.
- Message changes to "EXPIRED" once the countdown completes.

## Technologies Used

- HTML
- CSS (for styling the website)
- JavaScript

## Getting Started

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/aliza-fitness.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd aliza-fitness
   ```

3. **Open the `index.html` file** in your web browser.

4. **Customize the countdown date**:
   - Open `timer.js`.
   - Modify the `countDownDate` variable to set your desired countdown date and time.

   ```javascript
   // Set the date you're counting down to
   var countDownDate = new Date("Dec 31, 2024 23:59:59").getTime();
   ```

## Usage

- The timer will be displayed in the designated area of the website, showing how much time is left until the event or promotion.
- The countdown will continuously update until the target date and will display "EXPIRED" when the countdown ends.

## Example

Include the following element in your HTML to display the countdown timer:

```html
<div id="demo"></div>
```

## Installation

Make sure to include the necessary CSS and JavaScript files in your `index.html`:

```html
<head>
    <link rel="stylesheet" href="style.css">
    <script src="timer.js"></script>
</head>
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Aliza Hashmat** - [Your GitHub Profile](https://github.com/yourusername)
