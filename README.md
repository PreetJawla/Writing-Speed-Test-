# Typing Test

This is a simple typing test web application built with HTML, CSS, and JavaScript. It allows users to test their typing speed and accuracy.

## Features

-   Displays a predefined text for the user to type.
-   Starts a timer when the user begins typing.
-   Calculates and displays the user's Words Per Minute (WPM).
-   Calculates and displays the user's typing accuracy.
-   Displays the elapsed time.
-   Stops the timer and displays an alert when the user completes the test.

## How to Use

1.  Open the `index.html` file in your web browser.
2.  Start typing the text displayed in the test area.
3.  The timer will start automatically when you begin typing.
4.  Your WPM, accuracy, and elapsed time will be updated in real-time.
5.  When you finish typing the text correctly, an alert will appear, and the timer will stop.

## Files

-   `index.html`: The HTML structure of the web page.
-   `style` tags in the `<head>` of the html file: The CSS styles for the web page.
-   `script` tags at the end of the `<body>` of the html file: The JavaScript logic for the typing test.

## JavaScript Logic

-   The `startTimer()` function starts the timer and stores the start time.
-   The `updateTime()` function updates the displayed elapsed time every second.
-   The `checkInput()` function:
    -   Starts the timer if it hasn't started yet.
    -   Calculates the WPM based on the number of words typed and the elapsed time.
    -   Calculates the accuracy based on the number of correctly typed characters.
    -   Updates the displayed WPM, accuracy, and elapsed time.
    -   Checks if the user has completed the test. If so, it stops the timer and displays an alert.

## Customization

-   You can change the text to type by modifying the `text-to-type` paragraph in the `index.html` file.
-   You can customize the styling by modifying the CSS in the `<style>` tags.
-   You can adjust the timer interval in the `updateTime()` function by changing the `1000` (milliseconds) value.

## Example text to type.
The default example text is: "Type this text as fast as you can!"

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues.

## License

This project is open source.
