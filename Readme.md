# 🚗 Car Configurator 3D

**Car Configurator 3D** is a modular vehicle configurator built with **Unity, C#, URP, and WebGL**. It allows users to explore multiple vehicle models and customize different aspects of the vehicle with real-time visual updates.

The project focuses on creating a **modular, scalable, and web-friendly architecture**, using **Unity Addressables** to load vehicle assets, materials, and variants on demand.

## ✨ Features

* 🚘 **Multiple Vehicle Models**

  * Browse and switch between different vehicle configurations.
  * Vehicle content is loaded dynamically using Addressables.

* 🎨 **Vehicle Customization**

  * Change exterior paint colors and materials.
  * Switch between different wheel variants.
  * Customize interior options.
  * Apply changes with real-time visual feedback.

* 📦 **Dynamic Asset Loading**

  * Uses **Unity Addressables** for on-demand asset delivery.
  * Reduces the initial WebGL application size.
  * Allows new vehicles and customization content to be added independently.

* 🚪 **Interactive Vehicle Parts**

  * Open and close vehicle doors.
  * Toggle vehicle lights.
  * Provides an interactive vehicle showcase experience.

* 🎥 **Camera Controls**

  * Smooth orbit controls around the vehicle.
  * Zoom in/out for detailed inspection.
  * Scripted camera movement for a polished presentation.

* 🏠 **Exterior & Interior Modes**

  * Dedicated exterior viewing mode.
  * Interior viewing mode for exploring the vehicle cabin.
  * Camera behavior adapts to the selected viewing mode.

* 🌐 **WebGL Optimized**

  * Designed for browser-based interaction.
  * Uses URP and optimized asset delivery for a lightweight web experience.

## 🛠️ Tech Stack

* **Unity**
* **C#**
* **Universal Render Pipeline (URP)**
* **Unity Addressables**
* **WebGL**

## 🧩 Architecture Highlights

The project is designed around reusable and modular systems rather than vehicle-specific logic.

### Vehicle Configuration

Vehicle customization is handled through configurable variants, allowing different vehicles to share the same underlying systems while providing their own:

* Paint options
* Wheel options
* Interior options
* Interactive components
* Camera configurations

### Addressables-Based Content

Vehicle models and customization assets are separated from the initial application build and delivered through **Unity Addressables**.

This allows the project to:

* Keep the initial WebGL download smaller.
* Load content only when required.
* Add or update vehicle content independently.
* Reuse common configuration systems across multiple vehicles.

### Interactive Systems

Vehicle interactions are handled through reusable scripts for components such as:

* Doors
* Lights
* Camera controls
* Exterior/interior transitions
* Vehicle customization

## 📋 Requirements

* **Unity 6** or compatible Unity version
* **Universal Render Pipeline (URP)**
* **Addressables**
* **WebGL Build Support**

## 🚀 Project Highlights

This project demonstrates practical experience with:

* Modular Unity architecture
* Reusable C# systems
* Runtime vehicle customization
* Unity Addressables
* WebGL deployment
* URP rendering
* Interactive 3D environments
* Camera systems
* Asset management and dynamic content loading
* Performance-conscious web applications

## 📸 Screenshots
[Screenshot1](Screenshots/CarConfigurator3D_1.png)
[Screenshot2](Screenshots/CarConfigurator3D_2.png)
[Screenshot3](Screenshots/CarConfigurator3D_3.png)
[Screenshot4](Screenshots/CarConfigurator3D_4.png)
[Screenshot5](Screenshots/CarConfigurator3D_5.png)
[Screenshot6](Screenshots/CarConfigurator3D_6.png)
[Screenshot7](Screenshots/CarConfigurator3D_7.png)

## 🌐 WebGL Demo

**▶ [Launch Car Configurator 3D](https://mrabhisheq.github.io/CarConfigurator3D)**

## 📄 License

This project is intended for portfolio and demonstration purposes.
