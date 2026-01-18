# Garval Store

A beautiful e-commerce frontend for Finca Garval olive oil, built on Frappe/ERPNext.

## Features

- **Bilingual Support**: Spanish and English with easy language switching
- **ERPNext Integration**: Uses ERPNext Items, Customers, and Sales Orders
- **Modern Design**: Inspired by fincagarval.com with responsive layouts
- **Full E-commerce**: Shop, Cart, Checkout, Customer Accounts

## Pages

- `/home` - Homepage with hero, features, and featured products
- `/about` - About Us page with company story
- `/contact` - Contact form with communication integration
- `/shop` - Product listing with filters and sorting
- `/product/<slug>` - Product detail page
- `/cart` - Shopping cart (localStorage based)
- `/checkout` - Checkout with ERPNext Sales Order creation
- `/login` - Customer login
- `/signup` - Customer registration (creates ERPNext Customer)
- `/my-account` - Customer dashboard with order history

## Installation

```bash
# From frappe-bench directory
bench get-app garval_store /path/to/garval_store
bench --site your-site install-app garval_store
bench build
```

## Configuration

1. Add products in ERPNext as Items or Website Items
2. Set up Price Lists for pricing
3. Configure E Commerce Settings
4. Add images to `/assets/garval_store/images/`

## Required Images

See `garval_store/public/images/README.md` for the list of required images.

## License

MIT
