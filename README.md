# E-Phoenix Shift Sales V4

Standalone shift-sales calculator. It does not connect to or modify the E-Phoenix hotel website.

## Run
1. Install Node.js 18+.
2. Open this folder in a terminal.
3. Run `npm start`.
4. Open `http://localhost:3000`.

## V4 workflow
- No login/authentication.
- Staff enters their name, outlet and date.
- Starting again with the same staff + outlet + date resumes that person's OPEN shift.
- Drinks and Food/Combo are separate categories.
- Search products independently; a product can only appear once in a shift.
- Quantity can be typed directly or increased with quick controls.
- Drinks Total, Food Total and Grand Total are calculated automatically.
- Cash, Transfer and Card/POS are reconciled against Grand Total.
- Save preserves an open shift; Close Shift locks it.
- Final report groups Drinks and Food/Combo and shows Sold + Amount.
- Mobile-first sticky Save and Payment controls.

Current persistence is server-side local JSON. Move to a dedicated hosted database before multi-device production use.
