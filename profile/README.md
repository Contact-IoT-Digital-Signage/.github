# Contact-IoT Digital Signage Application

Built for the DevWeek 2023 Hackathon's Zoom SDK and Oracle Microservices Challenges

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

This project is a kiosk device application that connects customers to call center agents via the zoom sdk. After the call, our application utilizes OCI's mediaflow  machine learning service to transcript the recording data to text, automatically sorting into categories for future use in quality assurance, FAQ tables, call script generation, and countless other applications. Our application is deployed to Azure Functions (with Azure - OCI Interconnect).

## Deployed Application

- [kiosk app](https://contact-digital-signage-app.s3.us-west-1.amazonaws.com/index.html)
- [admin app](https://developerweek2023.web.app/) (Guest Account: u=testuser1@example.com, p=PASSWORD)

## Video Presentation

[![video presentation](https://user-images.githubusercontent.com/102705118/219301158-5e00c374-8e02-4fb2-83e3-e30716498824.png)](https://www.youtube.com/watch?v=XbxoET3iyCc)

## Techstack

- Backend: Oracle Cloud Interface (API Gateway, Vault, Functions, NoSQL, Media Flow, Object Storage)
- Frontend: Zoom SDK, Firebase Auth, React, MUI

## Our Team

- [Taro π―π΅ (Full Stack)](https://github.com/taro-ishihara)
- [Emeka π³π¬ (Backend)](https://github.com/EmekaU)
- [Sue π°π· (Backend)](https://github.com/suekim59)
- [JackJack πΊπΈ (Frontend)](https://github.com/JackYouk)

## License

This project is licensed under the terms of the [MIT license](https://opensource.org/licenses/MIT).
