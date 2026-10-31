# DouzePoints 🗳️⚡

> A high-concurrency, real-time voting simulation and admin control room inspired by the Eurovision Song Contest voting infrastructure.

## 🚀 Tech Stack (Target)

![Static Badge](https://img.shields.io/badge/Status-In%20development-yellow)
![Static Badge](https://img.shields.io/badge/Architecture-Decoupled-blue)
![Static Badge](https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql&logoColor=white)
![Static Badge](https://img.shields.io/badge/Laragon-Server-%230E83CD?logo=laragon&logoColor=white)
![Static Badge](https://img.shields.io/badge/PHP-8.x%20%7C%20PDO%20API-777BB4?logo=php&logoColor=white)
![Static Badge](https://img.shields.io/badge/Tauri-Admin%20App-%2324C8D8?logo=tauri&logoColor=white)
![Static Badge](https://img.shields.io/badge/React-Framework-%2361DAFB?logo=react&logoColor=white)
![Static Badge](https://img.shields.io/badge/Tailwind-Styling-%2306B6D4?logo=tailwindcss&logoColor=white)
![Static Badge](https://img.shields.io/badge/Rust-Core-%23000000?logo=rust&logoColor=white)
![Static Badge](https://img.shields.io/badge/Typescript-Safety-%233178C6?logo=typescript&logoColor=white)



## 🎯 Overview

**DouzePoints** is an experimental backend and systems engineering project built to study how live-production environments manage massive telemetry, dual-source scoring (professional juries vs. public televoting), and secure real-time data aggregation. 

This repository serves as a sandbox for exploring high-availability architectures, fault tolerance, and secure API endpoints under simulated high-load conditions.

---

## 🛠️ Planned System Architecture

- **Public Voting Portal:** Low-latency submission endpoints designed to handle high-concurrency bursts while mitigating spam and abuse.
- **Professional Jury Panel:** Role-based secure access for segregated point allocation (the iconic 1-8, 10, and 12 points).
- **Admin Control Room Dashboard:** Real-time scoreboard aggregation, live ranking shifts, and emergency failover toggles.
- **Data Integrity & Security:** Hardened API routing, input validation, and rate-limiting sandboxes to prevent vote spoofing or tampering.

---

## ⚠️ Disclaimer

*This project is for educational and portfolio purposes only. It is an independent system and is not affiliated with, endorsed by, or connected to the European Broadcasting Union (EBU) or the Eurovision Song Contest brand.*
