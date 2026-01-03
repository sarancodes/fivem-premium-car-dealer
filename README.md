# 🚗 Premium FiveM Car Dealership (MLO + Script)

A **high-quality premium car dealership system** for FiveM, featuring a luxury **dealership MLO**, immersive **showroom experience**, **test drive system**, and **secure vehicle purchase flow**.

Built for realism, performance, and easy integration with modern FiveM servers.

---
## 📂 Dependencies
- **Patoche Car Dealer MLO**  
  Credits and thanks to **Patoche** for the original dealership interior.

- **ox_lib**  
  Required for UI components, notifications, and shared utilities.

- **ox_target**  
  Used for smooth and interactive in-world interactions.

> ⚠️ Ensure all dependencies are installed and started **before** this resource.

---
## 📸 Screenshots

### Showroom & UI Previews

![Showroom – Image 1](https://github.com/sarancodes/fivem-premium-car-dealer/blob/main/2.jpg)

![Showroom – Image 2](https://github.com/sarancodes/fivem-premium-car-dealer/blob/main/6.jpg)

![Showroom – Image 3](https://github.com/sarancodes/fivem-premium-car-dealer/blob/main/location_blip.png)

---

## ✨ Features

### 🏢 Dealership MLO
- Luxury, modern dealership interior
- Optimized MLO with proper LODs & lighting
- Showroom floor, reception, office & delivery bay
- Night lighting & reflections for premium feel

### 🚘 Showroom System
- Dynamic showroom vehicles (config-driven)

### 🧪 Test Drive System
- Dedicated test drive spawn

### 💰 Vehicle Purchase
- Buy via cash / bank
- Auto plate generation
- Vehicle ownership saved to database
- Garage integration ready

---

## 🧠 Framework Support
- ESX (legacy & new)
- QBCore
- Standalone (basic mode)

---
## 📦 Download & Installation

1. Download the latest version from the **Releases** section of this repository.
2. Extract the downloaded file.
3. Place the resource folder into your server’s `resources/` directory.
4. Add the following lines to your `server.cfg` (ensure dependencies are started first):

```cfg
ensure ox_lib
ensure ox_target
ensure car_showroom



