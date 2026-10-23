# BuggyBay - Multi-Vendor E-Commerce Platform Suite

[![Flutter](https://img.shields.io/badge/Built%20With-Flutter-02569B?logo=flutter&logoColor=white)](#)
[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)](#)
[![Suite](https://img.shields.io/badge/Ecosystem-Multi--Vendor%20Suite-7952B3)](#)
[![Payments](https://img.shields.io/badge/Payments-Stripe%20%7C%20Google%20Pay-635BFF?logo=stripe&logoColor=white)](#)
[![Backend](https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase&logoColor=black)](#)

A comprehensive, production-ready multi-vendor e-commerce platform suite built with Flutter. BuggyBay connects buyers, independent merchants, and platform administrators into a unified digital commerce ecosystem.

---

## 📱 Ecosystem Applications

The repository contains release builds for all three core pillars of the BuggyBay platform:

```
Ecommerce_app/
├── customer apk/
│   └── app-release.apk    # BuggyBay Vendor / Merchant App
├── vendor apk/
│   └── app-release.apk    # BuggyBay Customer / Buyer Shopping App
├── web admin/
│   └── app-release.apk    # Multi-Vendor Platform Admin Application
├── .gitignore             # Git ignore configuration
└── README.md              # Project documentation
```

---

## 🌟 Key Features

### 🛒 1. Customer Shopping App (`com.buggybay.app`)
- **Smart Catalog & Discovery**: Categorized product discovery, lightning-fast search, filter by price, rating, and brand.
- **Cart & Wishlist**: Intuitive cart management with real-time price calculations, coupons, and discount support.
- **Secure Multi-Payment Gateway**: Integrated with **Stripe**, **Google Pay**, and **ShopPay** for friction-free, secure card and digital wallet transactions.
- **Live Order Tracking**: End-to-end shipment and delivery status tracking with real-time status updates.
- **Push Notifications**: Instant alerts for discounts, order confirmations, and dispatch notifications via Firebase Cloud Messaging.

### 🏪 2. Vendor / Merchant App (`com.buggybay.vendor`)
- **Storefront & Profile Management**: Complete control over store branding, operating hours, and vendor profiles.
- **Product & Inventory Management**: Add new products, upload images, manage variants (sizes, colors), and track stock levels in real time.
- **Order Fulfillment**: Review incoming customer orders, update fulfillment statuses (Processing, Shipped, Delivered), and manage cancellations.
- **Sales & Revenue Insights**: Track daily, weekly, and monthly sales performance and payout summaries.

### 🛠️ 3. Web Admin / Operations App (`com.example.multi_vendor_webapp`)
- **Vendor Onboarding & Approvals**: Review and verify merchant registrations and store legitimacy.
- **Global Catalog Moderation**: Oversee product categories, subcategories, tags, and promotional banners across the marketplace.
- **Platform Analytics**: High-level reporting on gross merchandise value (GMV), active users, and platform commissions.
- **User & Dispute Management**: Resolve buyer-seller disputes and enforce marketplace safety policies.

---

## 📦 Application Release Specifications

| Component | Directory | Application Name | Package ID | Key Technologies |
|---|---|---|---|---|
| **Customer App** | [`vendor apk/app-release.apk`](vendor%20apk/app-release.apk) | `BuggyBay` | `com.buggybay.app` | Flutter, Stripe, Google Pay, Firebase |
| **Vendor App** | [`customer apk/app-release.apk`](customer%20apk/app-release.apk) | `BuggyBay Vendor` | `com.buggybay.vendor` | Flutter, Firebase Auth, FCM, Image Picker |
| **Admin Console** | [`web admin/app-release.apk`](web%20admin/app-release.apk) | `multi_vendor_webapp` | `com.example.multi_vendor_webapp` | Flutter, Web & Android Support |

---

## 📲 Installation

To install the release build on an Android device:

1. Download the respective APK file from the repository or Releases section:
   - **Customer App**: [`vendor apk/app-release.apk`](vendor%20apk/app-release.apk)
   - **Vendor App**: [`customer apk/app-release.apk`](customer%20apk/app-release.apk)
   - **Admin App**: [`web admin/app-release.apk`](web%20admin/app-release.apk)
2. Enable **Install from Unknown Sources** in your Android device settings if prompted.
3. Open the downloaded `.apk` file and tap **Install**.

Alternatively, install via ADB:
```bash
# Install Customer Shopping App
adb install -r "vendor apk/app-release.apk"

# Install Vendor Merchant App
adb install -r "customer apk/app-release.apk"

# Install Admin Console App
adb install -r "web admin/app-release.apk"
```

---

## 🛠️ Repository Setup

### Cloning the Repository
```bash
git clone https://github.com/Akshaypayya/Ecommerce_app.git
cd Ecommerce_app
```

---

## 📄 License

This repository contains proprietary release builds for BuggyBay Multi-Vendor E-Commerce Platform. All rights reserved.
