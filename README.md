# CP to ECTS Calculator

A minimal, responsive calculator that converts course credit points (CP) into ECTS.

**Live Link**
https://cptoects.vercel.app/


## Formula

```
ECTS_course = CP_course × (60 × years_of_degree) ÷ total_credits_of_degree
```

Formula source: [Freie Universität Berlin](https://www.mi.fu-berlin.de/) credit conversion guidance.

### Example

A BSc degree has 120 CP over 4 years, and you took a 3 CP mathematics course:

```
ECTS = 3 × (60 × 4) ÷ 120 = 6
```

## Features

- Instant results as you type
- Shows the full calculation under the result
- Input validation with clear error messages
- Responsive layout for phones, tablets and desktops
- Automatic light and dark mode
- Single HTML file, no dependencies or build step

## Usage

1. Enter the course's **CP**.
2. Enter the **degree length** in years.
3. Enter the degree's **total credits**.
4. Read the **ECTS** result.

Use the **Use example** button to fill in sample values, or **Clear** to start over.

## Run locally

Download `cp-to-ects-calculator.html` and open it in any modern browser. No server needed.

```bash
git clone https://github.com/tasmim-tahsin/CP-to-ECTS-for-german-university-.git
cd CP-to-ECTS-for-german-university
open cp-to-ects-calculator.html
```

## Host on GitHub Pages (optional)

1. Rename `cp-to-ects-calculator.html` to `index.html`.
2. In your repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<your-repo>/`.

## Disclaimer

This tool gives an estimate based on a standard proportional formula. Universities may apply their own conversion rules, so confirm the final ECTS value with the institution you are applying to.

## Author

Made by **Tahsin**
