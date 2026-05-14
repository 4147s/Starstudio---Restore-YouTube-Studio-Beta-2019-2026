# Starstudio - Restore YouTube Studio 2019-2026 (Beta)

**Starstudio** is a comprehensive restoration project designed to bring back the legacy user interface and functional elements of YouTube Studio from the 2019-2020 era, meticulously updated for compatibility with the modern 2026 web environment.

## Project Vision
The transition to the "New" YouTube Studio left many creators missing the density, layout, and rapid-access workflows of the classic 2019 dashboard. Starstudio aims to bridge that gap by using high-performance DOM manipulation and CSS injection to reskin the current Studio experience into its legacy counterpart.

## Key Features
- **Classic Dashboard Reconstruction:** Re-implementation of the legacy card-based dashboard layout.
- **Analytics v2 Legacy Skin:** Restores the compact data views and navigation tabs for YouTube Analytics.
- **Enhanced Video Manager:** Reintroduces the 2019-style bulk editing interface and row density.
- **Dynamic CSS Injection:** Real-time skinning engine that adapts to YouTube's frequent back-end updates.
- **Performance Optimized:** Built with a modular architecture to handle the 38,000+ lines of codebase efficiently without slowing down the browser.

## Repository Structure
This repository is organized into several key modules:
- `/core`: The main engine logic for DOM monitoring.
- `/components`: Over 3,800 individual UI component handlers (found in `content.js`).
- `/styles`: Legacy CSS definitions and theme overrides.
- `/manifest.json`: Configuration for modern browser extension standards (Manifest V3).

## Installation for Developers
Since this project is currently in **Beta**, it is not available on public extension stores. To run it locally:
1. Clone this repository to your local machine.
2. Open your browser's Extension Management page (`chrome://extensions`).
3. Enable **Developer Mode**.
4. Click **Load unpacked** and select the directory containing these files.

## Technical Specifications
- **Target Version:** YouTube Studio 2019 (Legacy)
- **Compatibility:** 2024-2026 YouTube UI Frameworks
- **Lines of Code:** ~38,000 (Modular Architecture)
- **Language:** JavaScript (ES6+), CSS3, HTML5

## Contribution
We welcome contributions to the component registry. If you have a specific UI element from the 2019 era you wish to restore, please submit a Pull Request following our modular structure.

## Disclaimer
Starstudio is an independent project and is not affiliated with, authorized, maintained, sponsored, or endorsed by YouTube or Google.

---
*Created by 4147s - Bringing back the interface creators loved.*
