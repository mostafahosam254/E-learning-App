# 📱 Security Assessment – Android E-learning App

This repository contains a technical security report for an Arabic educational Android application.

## 🛡️ Overview

The app had previously faced issues with content leakage via developer tools and screen recording. A black-box security test was conducted in two phases:

1. **Initial scan** – Discovered multiple bypass vectors.
2. **Post-fix re-assessment** – Verified patches and found remaining issues.

## 🔍 Key Tested Areas

- Developer mode runtime protection
- Root detection and bypass
- Legacy Android support issues
- Screen recording prevention
- Watermarking for user identification

## 📋 Summary

The update fixed many previous issues, such as developer mode bypass and screen capture on older devices. However, the app still lacks:
- Strong root detection across all devices
- A dynamic watermarking system to trace content leakage

## 👨‍💻 Conducted by

**Mostafa Nassar**  
Cybersecurity Specialist & Penetration Tester  
📅 Scan date: April 18, 2025

## 📎 Files

- `Security_Report_Jomaa_App.pdf` – Full detailed report

---

> For any questions or collaborations, feel free to reach out on [LinkedIn](https://www.linkedin.com/in/YOUR-USERNAME).
