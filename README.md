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
## 🔧 Required Configuration Change

This resource uses **default GTA V vehicles**.  
You must update the showroom vehicle list to avoid addon car dependencies.

---

### 📁 File Location
car_showroom->config.lua
---

### ✏️ Configuration Update

Replace the existing `Config.ShowroomCars` with the following:

```lua
Config.ShowroomCars = {
    { model = 'adder',        price = 1000000, coords = vector4(-1256.94, -366.31, 36.18, 83.10), zOffset = 0.0 },
    { model = 'zentorno',     price = 725000,  coords = vector4(-1262.83, -353.76, 36.18, 39.72), zOffset = 0.0 },
    { model = 't20',          price = 2200000, coords = vector4(-1269.22, -363.61, 36.18, 92.38), zOffset = 0.0 },
    { model = 'schafter3',    price = 65000,   coords = vector4(-1244.23, -356.63, 40.09, 89.15), zOffset = 0.0 },
    { model = 'entityxf',     price = 795000,  coords = vector4(-1247.05, -351.81, 40.07, 81.42), zOffset = 0.0 }
}
```
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



