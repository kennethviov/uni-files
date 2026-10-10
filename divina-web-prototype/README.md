# DIVINA web prototype

A browser prototype based on the DIVINA Working Prototype section. Open `dist/index.html`, or run `node server.mjs` from this directory and visit http://127.0.0.1:4173.

The screen explorer displays 20 pages one at a time. The app buttons also connect the journey from filters and recommendations through trip details, seat coordination, booking summary, payment, confirmation, and My Trips.

The morning departure starts with 6 available seats. The afternoon departure starts with 4 available seats. Diver counts are capped at the available seats and totals update automatically. Demo payment creates a booking with a reference and saves it in browser local storage. Reset demo clears those example bookings. No real payment or account service is connected.

Design reference: https://www.figma.com/design/hXu6CY7EpcT2bvECTFHQ0P/DIVINA

Poppins, the pale lavender background, white rounded cards, blue pill buttons, and five-icon navigation follow the existing design. The supplied logo, dive photography, and map are included locally. Poppins is bundled locally, so the downloaded prototype also works without an internet connection.

Checked in the browser: both morning and afternoon booking paths, diver pricing, seat limits, all payment choices, booking confirmation, persistence across reloads, all 20 screens, and mobile overflow.
