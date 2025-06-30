# QR Code Generator CLI

A simple, high-performance command-line tool for batch-generating QR codes from URLs, text, contact info, and more.

---

## Table of Contents

1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Configuration](#configuration)  
6. [Examples](#examples)  
7. [Contributing](#contributing)  
8. [License](#license)  

---

## Features

- 📦 **Batch Mode**: Generate hundreds or thousands of QR codes in one go  
- 🔄 **Multiple Input Types**: URLs, plain text, vCards, Wi-Fi credentials, etc.  
- 🖼️ **Flexible Output**: PNG or SVG formats, custom dimensions  
- ⚡ **High Speed**: Optimized algorithm to cut generation time by 50%  
- 🔧 **CLI Flags**: Customize output directory, filename patterns, error correction level  

---

## Tech Stack

- **Node.js** (v14+)  
- **qrcode** npm package  
- **Commander** for CLI argument parsing  
- **Jest** for unit testing  

---

## Installation

```bash
# Clone the repo
git clone https://github.com/haswanth04/Qr-generator.git
cd Qr-generator

# Install dependencies
npm install

# Optionally, install globally for system-wide CLI use
npm install -g .
