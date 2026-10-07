# Traverse · Holiday Booking Website

A travel site for exploring and booking holiday destinations, with a user side and an admin side. Built with HTML, CSS and JavaScript as a team project at Masai School (Unit 3).

**Live site:** [travasure.netlify.app](https://travasure.netlify.app/) · **Portfolio:** [utkarash-thakur.vercel.app](https://utkarash-thakur.vercel.app)

<img width="100%" alt="Traverse home page" src="./Imgs/readme/screencapture-127-0-0-1-5501-index-html-2023-05-08-21_05_38.png">

## Highlights

- Multi-page site: sign-up and login, destination browsing, booking form, payment page and "My Bookings".
- Separate admin pages to see all bookings and to add, edit or delete destinations.
- Destinations come from a REST API (a JSON server); the logged-in user and their bookings are kept in `localStorage`.
- Holidays page with category filters, price and rating filters, sorting by price, and search by name.
- Scroll animations with the AOS library.

## Tech stack

HTML · CSS · JavaScript · JSON server (REST API) · AOS

## User side

- **Register and log in.** New users sign up with name, email, password and phone number.
- **Holidays.** Browse all destinations, filter by category, price and rating, sort by price, or search by name.
- **Book.** "Book Now" opens a form for name, email, phone, city, number of people, age and travel date. You must be logged in.
- **Pay.** Enter card details, then confirm with an OTP.
- **My Bookings.** See every booking you have made.

<img width="100%" alt="Holidays page" src="./Imgs/readme/Screenshot 2023-05-08 210645.png">
<img width="100%" alt="Booking form" src="./Imgs/readme/Screenshot 2023-05-08 210703.png">
<img width="100%" alt="Payment page" src="./Imgs/readme/Screenshot 2023-05-08 210722.png">
<img width="100%" alt="My Bookings page" src="./Imgs/readme/Screenshot 2023-05-08 221053.png">

## Admin side

- **Home:** all bookings.
- **Add destination:** name, description, image and price.
- **Destinations:** edit or delete any destination.

Demo admin login (sample data only): `utkarsh@travasure.com` / `travasure`.

<img width="100%" alt="Admin login page" src="./Imgs/readme/Screenshot 2023-05-08 205929.png">

## Run it locally

No build step. Clone the repo and open `index.html` in a browser, or use a local server such as the VS Code Live Server extension. The destination data is loaded from the hosted JSON server.

## Author

**Utkarash Thakur**, Backend Engineer · [Portfolio](https://utkarash-thakur.vercel.app) · [LinkedIn](https://www.linkedin.com/in/utkarash-thakur/)
