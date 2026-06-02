# EventPass 

### Facial Recognition & QR-Based Event Entry System

EventPass AI is a smart event management platform that streamlines event registration and verification. Users can register for an event, enroll their facial data, and gain entry through facial recognition, while a unique QR code serves as a secure backup authentication method.

---

## Project Overview

Traditional event check-ins can be slow and prone to manual errors. EventPass AI automates the registration and entry process by combining facial recognition technology with QR code verification.

The system allows event organizers to manage attendees efficiently while providing a fast, secure, and contactless check-in experience.

---

## Features

- Event registration system
- Attendee profile management
- Facial recognition-based entry verification
- Automatic QR code generation after registration
- QR code scanning as a backup authentication method
- Secure and contactless event check-in
- Event organizer dashboard

---

## Tech Stack

### Backend
- Python
- Django

### Database
- PostgresSQL

### Computer Vision
- OpenCV
- Face Recognition Library

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Additional Tools
- QR Code Generator
- Git
- GitHub

---

## System Workflow

1. User registers for an event.
2. User uploads facial data during registration.
3. The system stores facial encodings securely.
4. A unique QR code is generated for the attendee.
5. At the event entrance:
   - Facial recognition verification is attempted.
   - If recognition fails, the QR code can be scanned.
6. Attendance is recorded automatically.

---

### Planned Features
- Enhanced facial recognition accuracy
- Multi-event management support
- Attendance analytics dashboard
- Mobile-friendly user interface

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Apiiiil/EventPass---Face-detection.git
cd EventPass---Face-detection
