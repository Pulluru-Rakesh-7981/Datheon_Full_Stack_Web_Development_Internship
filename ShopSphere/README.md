# ShopSphere — Modern E-commerce Storefront

A responsive e-commerce demo built with HTML, CSS, and vanilla JavaScript. It uses a bold navy, violet, and blue visual theme with a custom shopping hero illustration and product data from [FakeStoreAPI](https://fakestoreapi.com/products).

## Features
- Modern gradient hero banner with shopping artwork
- Responsive navigation, product search, and category filters
- Product cards with images, prices, ratings, review counts, and badges
- Sorting by featured, price, and rating
- Slide-out cart with add, remove, increment, and decrement actions
- Cart saved in `localStorage`
- Subtotal, 8% estimated tax, $6.99 shipping under $75, and free shipping at $75+
- Simulated checkout with demo order confirmation
- Responsive desktop, tablet, and mobile layouts

## Run locally
Open `index.html` in a browser. If local file restrictions prevent API requests, run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files
- `index.html` — page structure
- `style.css` — responsive layout, gradient theme, cards, cart, and modal styling
- `script.js` — FakeStoreAPI integration, filters, cart, calculations, and checkout
- `hero-shopping-art.png` — decorative hero illustration

## Note
This is a learning/demo project. Checkout does not process real payments. FakeStoreAPI provides sample catalogue data; tax and shipping rates are demo values configured at the top of `script.js`.
