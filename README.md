# ShopEase E-Commerce App

A modern Flutter e-commerce application with beautiful UI and seamless user experience.

## Overview

ShopEase is a feature-rich e-commerce mobile application built with Flutter, providing users with a smooth shopping experience including product browsing, secure checkout, order tracking, and user profile management.

## Features

- Splash screen with Farm2Table branding
- Onboarding / welcome screen
- Login screen
- Product listing with category filters
- Product details screen
- Add to cart functionality
- Cart with quantity update
- Checkout screen with address and payment method
- Order placed confirmation
- Order tracking screen
- My Orders screen
- Profile screen
- Bottom navigation

## Screenshots

### Splash & Onboarding
<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/splash.png" width="200" alt="Splash Screen">
      <br><b>Splash Screen</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/onboarding.png" width="200" alt="Onboarding">
      <br><b>Onboarding</b>
    </td>
  </tr>
</table>

### Authentication
<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/login.png" width="200" alt="Login Screen">
      <br><b>Login</b>
    </td>
  </tr>
</table>

### Shopping Features
<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/home.png" width="200" alt="Home Screen">
      <br><b>Home</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/product_details.png" width="200" alt="Product Details">
      <br><b>Product Details</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/cart.png" width="200" alt="Shopping Cart">
      <br><b>Shopping Cart</b>
    </td>
  </tr>
</table>

### Checkout & Orders
<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/checkout.png" width="200" alt="Checkout">
      <br><b>Checkout</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/order_success.png" width="200" alt="Order Success">
      <br><b>Order Success</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/orders.png" width="200" alt="My Orders">
      <br><b>My Orders</b>
    </td>
  </tr>
</table>

### User Profile & Tracking
<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/profile.png" width="200" alt="User Profile">
      <br><b>User Profile</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/nethranekar88-tech/shopease_ecommerce_app/main/lib/screenshot/track_order.png" width="200" alt="Track Order">
      <br><b>Track Order</b>
    </td>
  </tr>
</table>

## Getting Started

### Prerequisites

- Flutter SDK (latest version)
- Dart SDK
- Android Studio or Xcode
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/shopease_ecommerce_app.git
cd shopease_ecommerce_app
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Project Structure

```
lib/
├── main.dart                 # Entry point
├── screenshot/               # App screenshots
└── [other folders]          # Additional modules
```

## Technologies Used

- **Flutter** - UI Framework
- **Dart** - Programming Language
- **Firebase/Backend** - Authentication & Data Storage
- **Provider/GetX** - State Management

## 🚀 Flutter Web Deployment (GitHub Pages)

This app is deployed and hosted on GitHub Pages for free! Access it live at:

🔗 **Live Demo:** https://nethranekar88-tech.github.io/shopease_ecommerce_app/

### Deployment Steps (10-15 minutes)

**Step 1: Build your app for web**
```bash
flutter build web
```
This creates a `build/web` folder with your web-optimized app.

**Step 2: Install gh-pages tool**
```bash
npm install -g gh-pages
```

**Step 3: Deploy to GitHub Pages**
```bash
gh-pages -d build/web
```

**Step 4: Enable GitHub Pages in your repository**
1. Go to your repository settings: `Settings → Pages`
2. **Source:** Select `Deploy from a branch`
3. **Branch:** Select `gh-pages`
4. **Folder:** Select `/ (root)`
5. Click **Save**

After 1-2 minutes, your app will be live at:
```
https://<your-username>.github.io/<your-repo-name>/
```

### Re-deploy after changes
Simply run these commands again:
```bash
flutter build web
gh-pages -d build/web
```

---

## Use Case

This app can be customized for:

- Grocery delivery business
- Farm product marketplace
- Vegetable and fruit ordering app
- Local store e-commerce app
- Food and essentials delivery app

## Project Status

Completed as a portfolio and client demo project.


**Developer**

- Nethra Nekar
- Flutter & FlutterFlow Developer
- GitHub: nethranekar88-tech
