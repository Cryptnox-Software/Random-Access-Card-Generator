**Hash: SHA256**

sha256sum cryptnox_random_access_card_generator.html
b0a016808eb2c33358a516c2aa759f0cdc28e3d89b1a2861bcd9a2de4893a6f1  cryptnox_random_access_card_generator.html

# Cryptnox Random Access Card Generator

A secure, standalone web application for generating random access cards with QR codes, PIN and PUK for Cryptnox wallets.

## Overview

The Cryptnox Random Access Card Generator is a privacy-focused, security-enhanced HTML application that creates unique access cards with QR codes and configurable PIN lengths. It operates entirely offline, ensuring complete data privacy and security.

## Features

### Core Functionality

- **QR Code Generation**: Create unique QR codes for each access card
- **Configurable PIN Length**: Choose between 4, 5, 6, 7, 8 or 9-digit PINs (Recommanded 9-digit PINs)
- **Batch Generation**: Generate multiple cards in a single session
- **Export Options**: Download cards as PDF or print directly
- **Offline Operation**: No internet connection required after initial load
- **Zero Data Collection**: All processing happens locally in your browser

### Security Features

- **Content Security Policy (CSP)**: Strict CSP headers prevent external resource loading
- **No External Dependencies**: All required libraries are embedded
- **No Tracking**: Completely respects user privacy with no analytics or tracking
- **Local Processing**: All card generation happens client-side
- **No Server Communication**: Operates entirely in the browser

## Usage

### Quick Start

1. **Open the Application**

   - Simply open `cryptnox_random_access_card_generator.html` in any modern web browser
   - No installation or setup required

2. **Configure Settings**

   - Select your desired PIN length (4, 5, 6, 7, 8 or 9 digits (Recommanded 9 digits))
   - Click "Generate Access Card"

3. **Export Your Cards**
   - Download as PDF for digital storage
   - Print directly for physical cards

### System Requirements

- Any modern web browser
- JavaScript enabled
- No internet connection required for operation

## Technical Details

### Built With

- **HTML5**: Core structure and layout
- **CSS3**: Modern styling with gradient backgrounds
- **JavaScript**: Application logic and card generation
- **QRCode.js**: QR code generation library (embedded)
- **jsPDF**: PDF generation library (embedded)

### Security Implementation

The application implements multiple layers of security:

```
Content-Security-Policy:
  - default-src 'none'
  - script-src 'self' [specific hashes]
  - No external resource loading
  - No form submissions
  - No iframe embedding
```

## Privacy & Data Protection

This application is designed with privacy as a priority:

- **No Data Storage**: Nothing is saved to servers
- **No Cookies**: No tracking or session data
- **No Analytics**: Complete privacy, no usage tracking
- **No External Requests**: All resources are self-contained
- **Local Processing**: Everything happens in your browser

---

## License

Copyright © Cryptnox. All rights reserved.

## Disclaimer

This access card generator is provided strictly for demonstration, testing, and educational purposes. They must not be used in production systems, financial applications, or in any situation where security, safety, or legal compliance is required.

Cryptnox SA makes no warranties, express or implied, regarding the accuracy, reliability, or suitability of the generated data. Use of this tool is entirely at your own risk. Cryptnox SA disclaims any and all liability for direct, indirect, incidental, or consequential damages arising from the use or misuse of the generated access cards.

By using this tool, you acknowledge and agree that the generated data does not create any contractual relationship, does not substitute for officially issued Cryptnox products, and cannot be relied upon for authentication or access control.

© Cryptnox SA. All rights reserved.
