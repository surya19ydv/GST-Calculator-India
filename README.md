# GST Calculator India

A free, instant, and beautifully designed Indian GST Calculator.
Built as part of the Digital Heroes project.

---

## Author

| Field | Details                          |
|-------|----------------------------------|
| Name  | Suryakala Yadav                  |
| Email | yadavsuryakala517@gmail.com      |

---

## Built for Digital Heroes

Visit: https://digitalheroesco.com

---

## Features

| Tab            | Description                                          |
|----------------|------------------------------------------------------|
| Exclusive GST  | Enter base price, calculates GST on top + total      |
| Inclusive GST  | Enter total price, extracts GST component from it    |
| Reverse GST    | Enter GST amount paid, finds base price and total    |
| Slab Compare   | Compare all 6 GST slabs side-by-side for any amount  |
| GST Rates Ref  | Searchable reference for common goods and services   |

### Additional Highlights
- CGST + SGST breakdown for intra-state transactions
- IGST breakdown for inter-state transactions
- All 6 GST slabs: 0%, 3%, 5%, 12%, 18%, 28%
- Copy to clipboard on results
- Enter key support on all input fields
- Fully responsive - works on mobile and desktop
- No data stored - 100% client-side, privacy-safe
- No login, no ads, no signup

---

## Design

- Color Palette : Orange (#f97316) + Olive Green (#6b8c1f) dark theme
- Typography    : Inter (Google Fonts)
- Style         : Glassmorphism, animated background glows, micro-animations
- Framework     : Pure Vanilla HTML + CSS + JavaScript (zero dependencies)

---

## Project Structure

gst-calculator/
  index.html   Complete single-file app (HTML + CSS + JS)
  README.md    This file

---

## How to Run

Option 1 - Open directly:
Double-click index.html in your file explorer. Opens in default browser.

Option 2 - Live Server (VS Code):
1. Install the Live Server extension in VS Code
2. Right-click index.html and select Open with Live Server
3. Visit http://127.0.0.1:5500/index.html

Option 3 - Deploy for free:
- Netlify Drop : https://app.netlify.com/drop  (drag and drop folder)
- GitHub Pages : https://pages.github.com/
- Vercel       : https://vercel.com/

---

## GST Formulas Used

| Calculation   | Formula                                                  |
|---------------|----------------------------------------------------------|
| Exclusive GST | GST = Base x Rate / 100   |   Total = Base + GST        |
| Inclusive GST | Base = Total x 100 / (100 + Rate)   |   GST = Total - Base |
| Reverse GST   | Base = GST Amount x 100 / Rate   |   Total = Base + GST  |
| CGST / SGST   | Each = GST / 2  (for intra-state)                       |
| IGST          | Full GST rate  (for inter-state)                         |

---

## GST Slabs Reference (FY 2024-25)

| Rate | Common Items                                      |
|------|---------------------------------------------------|
| 0%   | Fresh milk, vegetables, grains, pulses            |
| 5%   | Packaged food, economy air travel, railways       |
| 12%  | Mobile phones, business hotels, processed foods   |
| 18%  | Electronics, AC restaurants, IT services          |
| 28%  | Automobiles, luxury hotels, aerated drinks        |

Rates as per Government of India GST Act, 2017.

---

## License

Free to use for personal and educational purposes.

---

Made with love by Suryakala Yadav
Email: yadavsuryakala517@gmail.com