# Founders' Calendar booking page

The page the Iron Lady team uses to book time with Suvarna Hegde and Rajesh Bhat, and that the founders and the Founders' Office use to block time.

- Live at https://ironladytech.github.io/founders-calendar/. Every link carries its own code (`?k=...`, or `?cancel=...` from an invite). Without one, the page says the link is not valid.
- The page holds no data. Each request goes to the Founders' Calendar web app (Google Apps Script, run by ironladytech@gmail.com), which keeps the bookings on Google Calendar and in the "Iron Lady Founders' Calendar" sheet.
- It is hosted here, outside Google, so it opens for everyone whatever Google accounts they are signed in to.
- `index.html` is the same file as `Page.html` in the Apps Script project. When you change one, copy it to the other.
