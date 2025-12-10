# 🎨 3D Character Customization System

![Unity](https://img.shields.io/badge/Unity-2022.3.40f1-000000?style=flat&logo=unity)
![C#](https://img.shields.io/badge/C%23-Scripting-239120?style=flat&logo=c-sharp)
![Status](https://img.shields.io/badge/Status-Prototype-blue)

> A modular 3D character creation tool allowing real-time customization of facial features, armor sets, hairstyles, and colors.

---

## 📖 Project Overview

This project demonstrates a **runtime character customization system** in Unity. It allows players to modify the appearance of a 3D character through a UI interface, showcasing technical proficiency in **Mesh manipulation**, **Material management**, and **Object-Oriented design**.

The goal was to create a scalable system where new customization options (e.g., new armor pieces or hair types) can be added easily without rewriting the core logic.

---

## 🛠️ Key Features

### 1. Appearance Customization
The system allows users to swap mesh parts and modify visual properties in real-time:
* **Face Customization:** Toggle between different facial structures or expressions.
* **Hairstyles:** Swap different hair meshes dynamically.
* **Armor & Clothing:** Modular armor system allowing players to mix and match different equipment pieces.

### 2. Color Modification System
* Implemented a **Dynamic Color Picker** logic.
* Users can adjust the **RGB values** of the character's skin, hair, and armor materials individually.
* Changes are applied instantly using Unity's Material system.

### 3. Interactive UI
* Designed a user-friendly interface to navigate between customization categories (Face, Body, Gear).
* Real-time preview of the character as changes are applied.

---

## ⚙️ Technical Details

* **SkinnedMeshRenderer Manipulation:** The core system works by swapping references in the `SkinnedMeshRenderer` to change body parts while keeping the animation rig intact.
* **Material Instances:** Used material instances to ensure color changes apply only to the specific character part without affecting shared assets.
* **Scalable Architecture:** The code is structured to support ScriptableObjects (planned) for easily adding new item databases.

---

## 📸 Screenshots

<div align="center">
  <a href="https://www.linkedin.com/posts/erdogancolak_merhaba-de%C4%9Ferli-linkedin-ba%C4%9Flant%C4%B1lar%C4%B1m-geli%C5%9Ftirmekte-activity-7260704082162556928-FFQj?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD3OeJABrUqzthwfxiLdE5p2nSauQEkOXlc" target="_blank">
    <img src="https://img.shields.io/badge/Watch_Demo_Video-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Watch Demo"/>
  </a>
</div>

<br>

| Character Base | Armor & Color Customization |
| :---: | :---: |
| <img width="100%" alt="Base1" src="https://github.com/user-attachments/assets/b5c89023-9771-47b4-b21f-c5670eaa6d43" /> | <img width="100%" alt="Customized1" src="https://github.com/user-attachments/assets/21258d1a-ce84-4a60-b985-8dfc584f9db8" /> |
| <img width="100%" alt="Base2" src="https://github.com/user-attachments/assets/327ed00e-2785-4620-a7cb-9c2623b78f8e" /> | <img width="100%" alt="Customized2" src="https://github.com/user-attachments/assets/87b1fd2a-fdcf-4621-8bc5-180010911d91" /> |


---

## 🚀 Future Roadmap

- [ ] **Save/Load System:** Implement JSON serialization to save created characters.
- [ ] **BlendShapes:** Add detailed facial sliders (nose size, eye shape) using BlendShapes.
- [ ] **Animation Integration:** Allow users to play different emotes while customizing.

---

### 👨‍💻 Developer
Developed by **[Erdoğan Çolak](https://www.linkedin.com/in/erdogancolak/)**
