# HomeMade Pickles & Snacks - E-commerce App

## 📋 App Structure
```
homemade-main/
├── app.py                 # Main Flask app (routes, auth, checkout)
├── TODO.md               # Development tasks
├── static/
│   └── images/           # Product images (pickles, snacks)
├── templates/
│   ├── index.html        # Landing page
│   ├── login.html        # Login form
│   ├── signup.html       # Signup form
│   ├── home.html         # Dashboard with product previews
│   ├── veg_pickles.html  # Veg products + add to cart
│   ├── non_veg_pickles.html # Non-veg products
│   ├── snacks.html       # Snacks products
│   ├── cart.html         # Shopping cart (localStorage)
│   ├── checkout.html     # Checkout form with payment
│   └── success.html      # Order confirmation
```

## 🚀 Quick Start
1. **Run server:**
   ```
   python app.py
   ```
2. **Test flow:**
   - localhost:5000 → Signup/Login (`testuser`/`testpass`)
   - Home → Pickles/Snacks → Add to Cart
   - Cart → Checkout → Payment → Success!

## 🛒 Features
- **Auth**: Local users (signup/login)
- **Products**: Veg/Non-Veg Pickles, Snacks (6+ each)
- **Cart**: Client-side localStorage, server sync option
- **Checkout**: Form validation, local orders list
- **Responsive**: Mobile-first design

## 🔧 Local Development
- No AWS/DynamoDB needed (mocked data)
- `users` dict, `orders` list
- Add products in `app.py` `products` dict

## 📱 Flow
```
Landing → Login → Home → Products → Add Cart → Cart → Checkout → Success
```

Enjoy your homemade pickles shopping! 🥒
