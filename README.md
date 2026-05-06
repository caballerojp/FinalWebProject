# 🌲 Baguio Guides - Accessible Travel Companion

[![Accessibility](https://img.shields.io/badge/Accessibility-WCAG_2.1_AA-3a9b3a)](https://www.w3.org/WAI/standards-guidelines/wcag/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A fully accessible, responsive web application that serves as a comprehensive travel guide for Baguio City, Philippines. Features interactive maps, tourist spot information, user reviews, and real-time weather data.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Live Demo](#live-demo)
- [Installation](#installation)
- [Usage](#usage)
- [Accessibility Features](#accessibility-features)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## 🎯 Overview

Baguio Guides is a travel information platform designed to help visitors explore the "City of Pines" with ease. The application provides detailed information about 17+ tourist attractions, an interactive map with location pins, user review system, and real-time local information including weather and time.

**Target Audience:** Tourists, travelers, locals, and anyone planning to visit Baguio City

## ✨ Features

### Home Page (`index.html`)
- **Dynamic Attraction Cards** - 17 tourist spots with images and descriptions
- **Modal Information Windows** - Click any card for detailed attraction info including location, hours, tips, and directions
- **Real-Time Weather** - Current temperature in Baguio via Open-Meteo API
- **Live Clock** - Local time display updating every second
- **Random Spot Recommendation** - Daily suggestion for visitors
- **Responsive Grid Layout** - Works on desktop, tablet, and mobile

### Interactive Map (`map.html`)
- **Google Maps Integration** - Interactive map of Baguio City
- **Location Navigation** - Click any tourist spot to instantly navigate on map
- **Active Highlighting** - Currently selected spot is visually highlighted
- **Map Controls** - Zoom, pan, and full interactive map features
- **Spot-to-Map Linking** - Links from modals on home page bring you directly to specific locations on map

### Reviews Page (`review.html`)
- **Review Submission Form** - Name, place visited, and review text
- **Dynamic Review Display** - New reviews appear at the top of the list
- **Form Validation** - All fields required before submission
- **Success Confirmation** - Visual feedback after successful submission
- **XSS Protection** - HTML escaping for user-submitted content

### Universal Features
- **WCAG 2.1 AA Compliant** - Accessible to users with disabilities
- **Keyboard Navigation** - Full functionality without mouse
- **Screen Reader Compatible** - Proper ARIA labels and semantic HTML
- **High Contrast Focus Indicators** - Yellow outline for keyboard focus
- **Skip Navigation Link** - Jump directly to main content
- **Responsive Design** - Works on all screen sizes
- **Consistent Navigation** - Same header and footer across all pages

## 📁 Project Structure
