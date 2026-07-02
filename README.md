# Age Calculator

A lightweight, single-page web app that calculates a person's exact age in years, months, and days from their date of birth — plus total days lived and a countdown to their next birthday.

## Features

- 📅 **Date of Birth Input** — simple date picker, no manual typing required
- 🔢 **Exact Age Breakdown** — displays age in years, months, and days simultaneously
- 📊 **Total Days Lived** — running count of total days since birth
- 🎂 **Next Birthday Countdown** — shows how many days remain until the next birthday
- ⚡ **Instant, Client-Side Calculation** — updates live as soon as a date is selected, no server or page reload needed

## Tech Stack

| Layer       | Technology            |
|--------------|-------------------------|
| Structure     | HTML                    |
| Styling         | CSS                      |
| Logic            | Vanilla JavaScript (Date API) |

## How It Works

1. User selects a date of birth using the date input.
2. On input, JavaScript calculates the difference between the current date and the date of birth.
3. Years, months, and days are computed with calendar-aware logic (accounting for varying month lengths).
4. Total days lived is calculated from the millisecond difference between the two dates.
5. The next birthday is calculated by comparing today's date to this year's (or next year's, if already passed) birthday date.

## Getting Started

### Installation

```bash
git clone https://github.com/Kasthuri-001/age-calculator.git
cd age-calculator
```

### Run Locally

Simply open `index.html` in any modern browser:

```bash
open index.html
```

No build step, dependencies, or server required.

## Project Structure

```
age-calculator/
├── index.html      # Markup and layout
├── style.css        # Styling
├── script.js         # Age calculation logic
└── README.md
```

## Example

Input: `2000-05-15`
Output:
- **Age:** 26 years, 1 month, 17 days
- **Total days lived:** 9,545
- **Next birthday:** 317 days away

*(Values shown are illustrative — actual output depends on today's date.)*

## Future Improvements

- [ ] Add support for age calculation in different time zones
- [ ] Show age in additional units (weeks, hours)
- [ ] Add a shareable "age card" export (image/PDF)
- [ ] Dark/light theme toggle

## Author

**Kasthuri**

GitHub: [Kasthuri-001](https://github.com/Kasthuri-001)

## License

This project is open source and available under the [MIT License](LICENSE).
