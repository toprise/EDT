# Universal Encryption & Decryption Tool

This web application provides a versatile interface for multiple cryptographic operations, designed for secure and efficient data protection. Below is an overview of its main functionalities:

## Key Management
- **RSA Key Pair Generation:**  
  Generate RSA key pairs with selectable key lengths (e.g., 512, 1024, 2048 bits).
- **Save and Load Keys:**  
  Easily store your generated keys locally and retrieve them when needed.

## Text Encryption & Decryption
- **Encryption Methods:**  
  Supports both asymmetric encryption (RSA-OAEP, RSAES-PKCS1-V1_5) and symmetric encryption (AES-CBC).
- **Decryption:**  
  Decrypt messages that were encrypted using the corresponding encryption algorithm.

## Hash and HMAC Calculation
- **Hash Generation:**  
  Compute message digests using SHA-256, SHA-512, or MD5.
- **HMAC Creation:**  
  Generate keyed-hash message authentication codes (HMAC) to ensure data integrity.

## QR Code Generation
- **Dynamic QR Codes:**  
  Convert any text input to a QR code with high error correction for improved readability.

## File Encryption & Decryption
- **File Operations:**  
  Encrypt and decrypt files using RSA-OAEP or AES-CBC.
- **Password-Based AES Encryption:**  
  Use a password (with a minimum of 16 characters) to securely encrypt file data.

## Usage Quota & Advanced Features
- **Usage Quota:**  
  Each cryptographic operation (key generation, encryption, decryption, hashing, HMAC, QR code, file encryption/decryption) consumes one unit from a limited usage quota.
- **Advanced Unlock Feature:**  
  Unlock unlimited usage by entering valid credentials. The input password is processed via SHA-512 hashing for secure verification.
- **Persistent State:**  
  The tool uses cookies or local storage to persist the unlock status and remaining usage quota across sessions.

## Theme & Language Customization
- **Theme Switching:**  
  Flip between light and dark modes, and customize the interface using pre-defined color themes.
- **Language Support:**  
  The interface supports both English and Chinese, with dynamic text updates based on your language preference.

## User-Friendly Design
- **Consistent UI:**  
  All controls (buttons, text fields, dropdowns) are designed to be responsive, ensuring a seamless user experience across various devices.
