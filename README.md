# Simple Interest Calculater

A lightweight, browser-based Simple Interest Calculator built with HTML, CSS, and JavaScript. Enter a principal amount, choose an interest rate with a slider, pick the number of years, and instantly see the interest earned and total amount you'll receive.

## Features

- **Principal input** — enter any deposit amount as a number.
- **Interest rate slider** — drag between 1% and 20% in steps of 0.25%, with the selected rate displayed live next to the slider.
- **Years input** — type a value or pick a suggested year (1–10) from the built-in dropdown list.
- **Instant calculation** — clicking **Compute** calculates simple interest and displays the results.
- **Input validation** — alerts the user and refocuses the principal field if a non-positive amount is entered.
- **Simple, clean UI** — centered card layout with a dark page background for contrast.

## How It Works

The calculator uses the standard simple interest formula:

```
Interest = (Principal x Rate x Years) / 100
Amount   = Principal + Interest
```

It also calculates and displays the future year in which the deposit matures (current year + number of years entered).

## Project Structure

```
├── index.html   # Page markup and structure
├── script.js    # Calculation logic and UI interactivity
└── style.css    # Styling for the calculator card and page
```

## Usage

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Enter the deposit **amount**.
4. Adjust the **rate** slider to your desired interest rate.
5. Enter or select the **number of years**.
6. Click **Compute** to view the interest earned and total amount.

## Technologies Used

- **HTML5** — page structure and form elements (`input`, `range`, `datalist`)
- **CSS3** — styling and layout
- **JavaScript** — DOM manipulation and interest calculation logic

## Author

**Sreejoy Garg**
