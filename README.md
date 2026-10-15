# My Note:

This is what i did below.

# The KD Artisan Online Store

A practice online store for a local artisan business that sells handmade pottery, paintings and jewelry. It is built with HTML and CSS only.

**Live website:** (add your link here after you deploy)

## What the website has

- A homepage with a welcome message and an intro video
- A navigation bar that scrolls smoothly to each section
- Product cards for Pottery, Paintings and Jewelry (picture, title, price and an "Add to cart" button)
- An Inspiration section, an About section and a Contact section with a contact form
- A cart page section showing the items, quantities and total
- A checkout page with shipping and payment fields, and a thank-you page
- A layout that adjusts for desktop, tablet and mobile screens

## How to use the website

1. Open the homepage (`index.html`).
2. Use the navigation bar at the top to jump to Pottery, Paintings, Jewelry, Inspiration, the Cart, About or Contact.
3. Click **Add to cart** on a product to jump to the cart.
4. In the cart, click **Proceed to checkout**.
5. Fill in the shipping and payment form, then click **Place order**. You will see a thank-you page.

This is a **demo store**. No real payments are taken, so please do not enter real card details.

## Files

| File | What it does |
| --- | --- |
| `index.html` | The homepage, including products, cart, about and contact |
| `checkout.html` | The checkout form |
| `thanks.html` | The order confirmation page |
| `style.css` | All the styling and the responsive design |
| `README.md` | This file |

## Technologies used

- HTML5
- CSS3 (flexbox, media queries for responsive design, smooth scrolling)
- YouTube embedded video (`<iframe>`)

## Known limitations

This project uses only HTML and CSS, with no JavaScript. This means:

- The cart is a fixed example. Items cannot really be added or removed, and the total and the "Cart (3)" number do not update by themselves.
- The search bar and contact form do not work like a real shop's, because they need a server or JavaScript.
- The checkout is a demo and does not process payments.

## Testing

- Checked in different web browsers (Chrome, Firefox, Edge)
- HTML checked with the W3C Markup Validator (validator.w3.org)
- CSS checked with the W3C CSS Validator (jigsaw.w3.org/css-validator)