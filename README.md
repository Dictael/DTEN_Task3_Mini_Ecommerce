# Task 3 — Mini E-Commerce Product Page

## Requirements covered
- Responsive product catalogue.
- Search and category filtering.
- Shopping cart with add/remove, quantity controls and running total.
- Mock REST API connection using Fake Store API.
- Fallback demo products if the API is unavailable.
- Basic checkout form validation for name, email, phone and address.
- Cart state stored in localStorage.
- Mobile-friendly layout.

## Run locally
Open `index.html` in a browser or use VS Code Live Server. Because the project uses `fetch()`, Live Server is recommended.

## API
Primary endpoint: `https://fakestoreapi.com/products`

The app automatically falls back to a small local demo catalogue if the API cannot be reached.

## Deploy
This project is static HTML/CSS/JavaScript, so it can be deployed using GitHub Pages, Netlify or Vercel.

## Demo checkout
No real payment is taken. The checkout form demonstrates validation and a successful demo-order flow, as required for a mini e-commerce front end.
