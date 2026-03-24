# BIXI Montréal Live Dashboard 🚲

A real-time interactive dashboard for BIXI Montréal bike-sharing stations. View station locations, bike availability, and dock availability on an interactive map with a responsive mobile-friendly interface.

![Dashboard Preview](https://bixi-all-system.netlify.app/assets/image-web.jpeg)

## 📋 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Reference](#api-reference)
- [Mobile Responsiveness](#mobile-responsiveness)
- [Legal & Disclaimer](#legal--disclaimer)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## ✨ Features

- **Real-time Station Data** — Live bike and dock availability from BIXI's GBFS feed
- **Interactive Map** — Leaflet-powered map with custom bike markers for each station
- **Station Search** — Filter stations by name with instant results
- **Station Details** — Click any station card to center the map and view detailed info
- **Mobile-First Design** — Fully responsive layout that works on desktop, tablet, and mobile devices
- **Auto-Refresh** — Data updates every 45 seconds to ensure accuracy
- **Offline Banner** — Visual indicator when the system is unavailable
- **Legal Modal** — Terms of use, privacy policy, and disclaimer accessible via footer links

## 🚀 Demo

You can view a live demo of the dashboard at:  
**[https://your-demo-link.com](https://your-demo-link.com)** *(Add your deployment link here)*

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and content |
| **CSS3** | Styling, animations, responsive design |
| **JavaScript (ES6+)** | Application logic, API integration |
| **Leaflet.js** | Interactive mapping |
| **Font Awesome** | Icons and visual elements |
| **GBFS API** | Real-time BIXI station data |

## 📦 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection to fetch live BIXI data
- (Optional) Local web server for development

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/bixi-mtl-dashboard.git
   cd bixi-mtl-dashboard

   bixi-mtl-dashboard/
├── index.html              # Main application file
├── README.md               # Project documentation
├── css/                    # (Optional) External CSS
│   └── style.css
├── js/                     # (Optional) External JavaScript
│   └── app.js
└── assets/                 # (Optional) Images and assets
    └── screenshots/
