# Magento 2 Supplier-Based Shipping Module

## 🚀 Overview

A Magento 2 extension that calculates shipping charges dynamically based on supplier rules.

Supports multi-supplier carts, configurable charges, and supplier-wise free shipping thresholds.

---

## 🔥 Features

* Supplier-based shipping calculation
* Dynamic admin configuration (add multiple suppliers)
* Multi-supplier cart handling
* Free shipping rules per supplier
* Clean and scalable architecture

---

## ⚙️ How It Works

1. Assign supplier to each product
2. Configure supplier rules in admin:

   * Shipping charge
   * Free shipping threshold
3. During checkout:

   * Cart is grouped by supplier
   * Charges calculated per supplier
   * Final shipping cost is combined

---

## 📂 Example

| Supplier | Charge | Free Above |
| -------- | ------ | ---------- |
| ABC      | 15     | 1500       |
| XYZ      | 10     | 1000       |

---

## 🛠️ Installation

```bash
composer require vaibhav/module-supplier-shipping
php bin/magento setup:upgrade
php bin/magento cache:flush
```

---

## 📸 Screenshots

(Add screenshots here)

---

## 💡 Use Case

* Multi-vendor stores
* Marketplace systems
* Supplier-based shipping logic

---

## 👨‍💻 Author

Vaibhav Savani
Magento 2 Developer
