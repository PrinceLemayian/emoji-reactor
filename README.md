# Emoji Counter

A simple interactive web app that lets users click emoji buttons to increase their respective counts. Each button tracks its own count up to a maximum of 10, updating the displayed number dynamically.

---

## Features

* Clickable emoji buttons
* Live count update displayed on each button (`0/10 → 10/10`)
* Each button’s count is independent
* Prevents counts from exceeding the maximum limit

---

## How It Works

* Each button has a `.count` element showing its current value
* JavaScript `updateCount()` function handles:

  * Extracting the current count
  * Checking the maximum limit
  * Incrementing the count
  * Updating the displayed text
* Event listeners are added to all buttons using `forEach`
* Works with any number of buttons using the `.emoji-btn` class

---

## Technologies Used

* HTML
* CSS
* JavaScript (vanilla)

---

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/emoji-counter.git
   ```
2. Open `index.html` in your browser
3. Click on the emoji buttons to increment counts

---

## Notes

* Maximum count per button is **10**
* Can be easily extended to include more buttons or different max counts

---

## Author

Prince Lemayian – https://github.com/PrinceLemayian
