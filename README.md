# Orbit 🚀

<p align="center">
  <img src="https://img.shields.io/github/actions/workflow/status/AlexanderSolano/Orbit/dotnet.yml?branch=main&style=for-the-badge" alt="Build Status">
  <img src="https://img.shields.io/github/license/AlexanderSolano/Orbit?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/last-commit/AlexanderSolano/Orbit?style=for-the-badge" alt="Last Commit">
  <img src="https://img.shields.io/github/repo-size/AlexanderSolano/Orbit?style=for-the-badge" alt="Repo Size">
</p>

<p align="center">
  A modern, cross-platform application to seamlessly transfer files from your phone to your desktop over your local Wi-Fi network.
</p>

<p align="center">
  <a href="#-about-the-project">About The Project</a> •
  <a href="#-key-features">Key Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-roadmap">Roadmap</a> •
  <a href="#-contributing">Contributing</a> •
  <a href="#-license">License</a>
</p>

***

## 📋 About The Project

Orbit is a file transfer solution focused on simplicity, speed, and privacy. Unlike cloud-based solutions, all transfers occur directly between your devices on your local network, ensuring your data never leaves your control.

Device discovery is handled easily via QR code, eliminating the need to manually enter IP addresses.

***

## ✨ Key Features

* **Local Network Transfer:** Send files directly over Wi-Fi with no need for external servers.
* **QR Code Discovery:** Fast and error-free connection between mobile and desktop.
* **Cross-Platform:** Native support for Linux, macOS, Windows, Android, and iOS.
* **Robust Architecture:** Decoupled UI from a backend service for improved resilience.

***

## 🛠️ Tech Stack

This project is a monorepo containing the following packages:

* **⚙️ Backend Service (`Orbit.Service`):** .NET 8, ASP.NET Core
* **🖥️ Desktop App (`Orbit.Desktop`):** .NET 8, Avalonia UI
* **📱 Mobile App (`Orbit.Mobile`):** React Native, TypeScript

***

## 📂 Project Structure

The project follows a monorepo pattern to facilitate management and coherent development across platforms.
