# Sentirhy
<p align="center">
  <img src="./assets/logo.png" alt="Sentirhy logo" width="200" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Access-Project%20Showcase-1abc9c?style=for-the-badge" alt="Project Showcase" />
  <img src="https://img.shields.io/badge/Frontend-React-61dafb?style=for-the-badge&logo=react&logoColor=20232a" alt="React" />
  <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/API-Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/ML-TensorFlow-ff6f00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/Music%20Service-Spotify-1db954?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify" />
</p>

A facial emotion recognition web application that recommends music playlists based on the user's current emotional state.

> This repository is presented for portfolio and project showcase purposes.  
> The full source code is not publicly available.

---

## Overview

Sentirhy is a web-based application designed to combine **facial emotion recognition** with **music recommendation** to support a more personalised music therapy experience.

The system analyses a user's facial expression, identifies their emotional state, and generates a playlist that aligns with that mood. The goal of the project is to explore how machine learning and modern web technologies can be used to create an accessible, user-focused therapeutic tool.

---

## What the Project Does

The application allows users to:

- Register and log into a secure account
- Connect their Spotify account
- Use their camera for real-time facial emotion detection
- Identify emotions such as **happy**, **sad**, **angry**, and **neutral**
- Generate a playlist based on the detected emotion
- Play music through Spotify Web Playback
- Manage account settings and preferences

---

## Key Features

- Real-time facial emotion recognition
- Emotion-based playlist generation
- Spotify integration using OAuth 2.0
- User authentication and account activation
- Password hashing and secure session handling
- Responsive web interface
- User settings and profile management
- Light and dark theme support
- Multi-language support
- Step-by-step UI-driven user flow

---

## Project Motivation

This project was developed to explore the connection between **technology** and **mental well-being**.

Traditional music therapy can be effective, but it may not always be accessible in everyday settings. Sentirhy aims to show how emotion recognition and music recommendation can work together to provide a scalable and personalised experience that responds to a user's emotional state in real time.

---

## How It Works

1. The user logs into the application.
2. The user connects their Spotify account.
3. The application accesses the user's camera with permission.
4. A facial emotion recognition model analyses the captured frame.
5. The system identifies the user's emotion.
6. A playlist is generated to match the detected mood.
7. The playlist is played through Spotify Web Playback.

---

## Tech Stack

### Web Application
- React
- Node.js
- Express.js
- PostgreSQL

### Machine Learning
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Scikit-learn

### Other Tools
- Spotify API
- OAuth 2.0
- Nodemailer
- Jupyter Notebook

---

## Architecture

The project is split into several main components:

- **Frontend:** handles the user interface and user interactions
- **Backend API:** manages authentication, data flow, and integration logic
- **Database:** stores user data, account details, and music-related records
- **Emotion Recognition Engine:** processes captured facial images and predicts emotion
- **Playlist Generation Logic:** selects suitable tracks based on the detected emotion
- **Spotify Integration:** enables music playback inside the application

This separation helps keep the system modular, maintainable, and easier to extend.

---

## Machine Learning Approach

The emotion recognition system was developed using convolutional neural networks (CNNs).

The model was trained using facial emotion datasets including FER-2013 and CK, with later transfer learning applied to improve performance across broader demographic variation. The final system focused on four core emotions:

- Neutral
- Happy
- Sad
- Angry

This scope was chosen to keep the recommendation logic practical and aligned with the project's music therapy goals.

---

## Security and Authentication

The application includes several security-focused features:

- Encrypted password storage using bcrypt
- Secure user authentication flow
- Account activation through email verification
- OAuth 2.0 integration for Spotify access
- Secure handling of user data and session tokens
- HTTPS-based communication requirements in the design

---

## Testing

The project was tested across both UI and backend functionality, including:

- User registration and login
- Account activation
- Password reset
- Spotify connection
- Music playback controls
- Emotion detection flow
- Playlist generation
- User settings updates

---

## Challenges Solved

Some of the main challenges addressed during the project included:

- Integrating machine learning into a working web application
- Handling real-time facial detection in the browser
- Training and tuning CNN models for emotion recognition
- Connecting Spotify playback into the application flow
- Balancing model accuracy with computational cost
- Managing scope and prioritising core features during development

---

## Limitations

While the project achieved its main objectives, there were still some limitations:

- Emotion recognition accuracy could vary under different lighting conditions
- Performance may be affected by unusual facial expressions
- YouTube integration was planned but not completed
- Scalability testing was limited
- Further optimisation could improve model efficiency and deployment readiness

---

## Future Improvements

Planned or possible future enhancements include:

- Expanding support for additional music services
- Improving model robustness across more diverse datasets
- Adding user feedback loops to improve recommendations
- Enhancing scalability and performance
- Refining the recommendation algorithm for more personalised results
- Extending accessibility and localisation features

---

## Screenshots

This repository can include:

- Login page
- Registration page
- Dashboard
- Emotion detection page
- User settings page
- Architecture diagrams
- Testing snapshots or demo walkthroughs

---

## Documentation

- [Project Dissertation (PDF)](./docs/Sentirhy-Dissertation-Yie-Nian-Chu.pdf)

## Repository Purpose

This public repository is intended to showcase:

- The project idea
- System design
- Technical architecture
- Features and user flows
- Development approach
- Project outcomes

It does **not** include the full implementation code.

---

## Author

**Yie Nian Chu**  
BSc Computer Science, University of the West of England

---

## License

Copyright (c) 2026 Yie Nian Chu. All rights reserved.

This repository is shared for viewing and portfolio purposes only.  
No permission is granted to copy, modify, distribute, sublicense, or use this work commercially without prior written consent.
