# 🏎️ BMW MX — Car Dealership Website

A sleek, responsive BMW M-series car dealership web project built with pure HTML, CSS, and vanilla JavaScript.


---

## 📁 Project Structure

```
bmw-mx/
├── project.html        # Main entry point — full dealership page
├── main.html           # Extended inventory page
├── main.css            # Core styles (hero, inventory cards, layout)
├── login.html          # User login page
├── login.css           # Login page styles
├── navbar.html         # Animated icon navbar component
├── navbar.css          # Navbar styles (expand-on-hover)
├── nav1.html           # Stripe-style dropdown mega menu
├── nav1.css            # Mega menu styles
├── nav2.html           # Full-screen animated navigation
├── nav2.css            # Full-screen nav styles
└── assets/
    └── bmw-m-logo.png  # BMW M Motorsport logo
```

---

## 🚀 Features

- **Hero Section** — Full-viewport BMW background with a bold CTA button
- **Inventory Cards** — Responsive grid of BMW M-series vehicles (M2, M3, M4, M5) with price, mileage, and "Add to Wish" functionality
- **Wishlist (Cart)** — JavaScript-powered wish list with alert confirmation
- **Login Page** — Clean, minimal login form with forgot password and sign-up links
- **Multiple Navbar Styles** — Three different navigation components included:
  - Animated expand-on-hover icon navbar
  - Stripe-inspired CSS-only dropdown mega menu
  - Full-screen hover-effect navigation
- **About & Contact Sections** — Footer with contact info and about blurb
- **Responsive Design** — Mobile-friendly layout using CSS Grid and Flexbox

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantics |
| CSS3 | Styling, animations, grid/flexbox layouts |
| Vanilla JavaScript | Wishlist/cart functionality |
| Google Fonts | Typography |
| Ionicons | Icon set for navbar |
| Font Awesome | Icons for mega menu |

---

## 🏁 Getting Started

No build tools or dependencies required — just open in a browser.

```bash
# Clone the repository
git clone https://github.com/your-username/bmw-mx.git

# Navigate into the folder
cd bmw-mx

# Open the main page
open project.html
```

Or simply double-click `project.html` to launch it in your default browser.

---

## 📸 Pages Overview

### `project.html` — Main Dealership Page
The primary landing page featuring the hero banner, BMW M-series inventory cards, about section, and footer. Includes a link to the login page.

### `login.html` — Login Page
A centered login card with username/password fields, forgot password link, and sign-up prompt.

### `navbar.html` — Icon Navbar
A pill-shaped navigation bar with icons that expand to show labels on hover, using Ionicons.

### `nav1.html` — Mega Menu (Stripe-style)
A CSS-only animated dropdown navigation inspired by Stripe's website, with sub-menus for Products, Services, Support, and Community.

### `nav2.html` — Full-Screen Nav
A large typographic navigation where hovering a link fills the screen background with a colored circle effect.

---

## 🎨 Color Palette

| Role | Color |
|---|---|
| Primary Background | `#353535` (Dark Gray) |
| Header / Footer | `#000000` (Black) |
| Accent / Price | `#ffcc00` (BMW Yellow) |
| Link / CTA | `#003580` (Deep Blue) |
| Card Background | `#ffffff` (White) |

---

## 📌 Known Issues / TODOs

- [ ] Wishlist data does not persist (no localStorage or backend yet)
- [ ] Duplicate inventory section in `main.html` (can be refactored)
- [ ] `addToCWish` typo in `main.html` (should be `addToWish`)
- [ ] Login form has no authentication logic yet
- [ ] "Details" buttons link to `#` — individual car detail pages not yet built
- [ ] About section still references "TravelX" — needs updated copy for BMW MX branding

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ and a passion for BMW M-series performance cars.
