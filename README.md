# 🌆 Shopno Jabe Bari – City to Village Life Transition with 2D Animation

**Shopno Jabe Bari** is a C++ OpenGL graphics project that visually illustrates the emotional transition between **city life** and **village life**.  
Through rich 2D animations, it highlights the contrast between fast, modern urban environments and the calm, peaceful nature of rural living.

---

## 👥 Project Team (Group Project)

This project is developed as a **group graphics project** by:

| Name |
|------|
| **Neloy** *(Md. Fardin Hossain Neloy)* |
| **Mowmita** |
| **Hazary** |
| **Protiom** |

---

## 🎥 Featured Animated Scenarios

This project includes four switchable visual environments:

| Scenario Key | Scene Description |
|--------------|------------------|
| `V` or `v` | **Main City** — buildings, flyovers, train, cargo truck, bus, clouds |
| `M` or `m` | **Bridge** — ambulance, multiple cars, water bridge animation |
| `A` or `a` | **Sub-City** — traffic, bus, clouds, roadside visuals |
| `S` or `s` | **Village** — trees, natural fields, cars, day/night ambience |

Also supports full **Day/Night transition** in all scenes.

---

## 🎮 Controls & User Interaction

### 🌞 General Controls (apply to all scenarios)

| Action | Key |
|--------|-----|
| Switch to **Day** mode | `D` or `d` |
| Switch to **Night** mode | `N` or `n` |
| Pause/Resume all animations | `Spacebar` |
| Exit application | `ESC` |

---

### 🏙 Main City Functionality

| Action | Input |
|--------|-------|
| Train speed up/down (Day) | `↑` / `↓` |
| Moon speed up/down (Night) | `→` / `←` |
| Pause/Resume all animations | `Spacebar` |
| Play/Pause Train (Day) | Mouse **Left Click** |
| Play/Pause Sun (Day) | Mouse **Right Click** |
| Play/Pause Moon (Night) | Mouse **Left Click** |
| Play/Pause Cargo Truck (Night) | Mouse **Right Click** |

---

### 🏙 Sub-City Functionality

| Action | Input |
|--------|-------|
| Pause/Resume all animations | `Spacebar` |
| Track speed up/down (Day/Night) | `↑` / `↓` |
| Cloud speed control (Night) | `→` / `←` |
| Play/Pause Bus | Mouse **Left Click** |

---

### 🌉 Bridge Functionality

| Action | Input |
|--------|-------|
| Speed up/down Car1 (Day/Night) | `↑` / `↓` |
| Increase Ambulance speed (Day) | `→` |
| Decrease/Reverse Ambulance speed (Day) | `←` |
| Play/Pause Car1 (Day) | Mouse **Left Click** |
| Play/Pause Train (Night) | Mouse **Right Click** |

---

### 🌾 Village Functionality

| Action | Input |
|--------|-------|
| Play/Pause Sun (Day) | Mouse **Left Click** |
| Play/Pause Car1 (Day) | Mouse **Right Click** |
| Pause/Resume all animations | `Spacebar` |
| Car1 speed control (Day) | `↑` / `↓` |
| Car2 speed control (Night) | `→` / `←` |

---

## 🛠 Technologies Used

| Component | Tech |
|----------|------|
| Language | C++ |
| Graphics Library | OpenGL & GLUT |
| Platform | Windows (MinGW / CodeBlocks / Visual Studio) |
| Rendering | 2D animation |

---

## 🚀 Build & Run Instructions

### ✔ Requirements
- C++ Compiler (GCC/MinGW/MSVC)
- OpenGL libraries
- GLUT / freeGLUT

### ▶ Build Command Example
```bash
g++ main.cpp -lopengl32 -lglu32 -lfreeglut -o ShopnoJabeBari.exe
./ShopnoJabeBari.exe
