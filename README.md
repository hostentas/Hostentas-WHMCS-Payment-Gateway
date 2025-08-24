# # Hostentas – WHMCS Payment Gateway Module

**Hostentas** is a lightweight, secure payment gateway integration for WHMCS. It allows your clients to make instant payments through the hostentas Pay API with real-time callback verification. Designed for hosting providers and digital service platforms using WHMCS.

---

## 🚀 Features

- 🔐 Secure token-based API integration
- ⚡ Real-time callback and payment verification
- 💱 Supports INR and multi-currency billing
- 🧩 Compatible with WHMCS 7.5 to 8.13+
- 🖥️ Easy admin setup and configuration
- 📄 Clean transaction logs for auditing
- 🔄 Manual and automatic payment confirmation supported

---

## 📦 Installation

### Step 1: Download

Download the latest release of `hostentas.zip` from:


### Step 2: Upload Files
/modules/gateways/hostentas.php
/modules/gateways/callback/hostentas.php


> ⚠️ If `/callback/` folder doesn't exist, create it manually.

---

### Step 3: Activate Gateway

1. Login to your WHMCS Admin Panel  
2. Navigate to: **Setup > Payments > Payment Gateways**  
3. In the list of Available Gateways, find **Hostentas** and click **Activate**

---

### Step 4: Configure Gateway Settings

Fill in the following fields:

- **API Token** – Required (Get it from your Hostentas Pay dashboard)
- **Merchant ID** – Optional (if used in your integration)
- **Route** – Set to 1, 2, or 3 depending on your routing configuration
- **Callback URL** – Set to:  
  `https://yourdomain.com/modules/gateways/callback/hostentas.php`

Click **Save Changes**.

---

## ⚙️ Requirements

- PHP 7.2 or higher
- WHMCS 7.5 or higher
- cURL extension enabled on your server
- A valid Hostentas Pay account

---

## 💡 Example WHMCS Gateway Settings

| Field        | Value Example                                                   |
|--------------|-----------------------------------------------------------------|
| Display Name | Hostentas                                                       |
| API Token    | j0u2c3d4e5f6g7h89h6fg                                            |
| Route        | 1 (You can set Route to 1, 2, or 3 based on your routing setup) |
| Callback URL | https://yourdomain.com/modules/gateways/callback/hostentas.php  |

**Route Options:**  
Use Route `1`, `2`, or `3` depending on your desired payout speed or backend routing configuration from your Hostentas Pay dashboard.

---

## 📷 Screenshots

1. Admin Configuration Screen  
2. Payment Method Selection  
3. Success Page or Invoice Paid Page

---

## 🔐 Security Tips

- Always keep your API token secret  
- Use HTTPS for your WHMCS installation  
- Rotate your API key regularly from your hostentas dashboard  

---

## 🛟 Support

Need help or have questions?

📧 Email: [smtechhost@gmail.com](mailto:smtechhost@gmail.com)  
🌐 Website: [https://smtechhost.in/contact](https://smtechhost.in/contact)  
📞 WhatsApp: [Click Here](https://wa.me/918617507639)

---

## 📜 License

This project is licensed under the MIT License.  
See the [LICENSE.txt](LICENSE.txt) file for full license text.

---

## 🧾 Changelog

### v1.0.0 – 22 August 2025

- Initial release  
- Hostentas Pay WHMCS integration  
- Callback & live payment verification  

---

## 🙌 Credits

Developed and maintained by **hostentas Technologies**  
Visit: [https://smtechhost.in](https://smtechhost.in)


Unzip the downloaded file and upload the contents to your WHMCS installation directory:

<hr>
<p align="center">
  Developed with ❤️ by <strong>Souvik Manna</strong>
</p>
 – WHMCS Payment Gateway Module

**Hostentas Pay** is a lightweight, secure payment gateway integration for WHMCS. It allows your clients to make instant payments through the hostentas Pay API with real-time callback verification. Designed for hosting providers and digital service platforms using WHMCS.

---

## 🚀 Features

- 🔐 Secure token-based API integration
- ⚡ Real-time callback and payment verification
- 💱 Supports INR and multi-currency billing
- 🧩 Compatible with WHMCS 7.5 to 8.13+
- 🖥️ Easy admin setup and configuration
- 📄 Clean transaction logs for auditing
- 🔄 Manual and automatic payment confirmation supported

---

