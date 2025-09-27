# AnajSuraksha

### Problem

India’s Public Distribution System (PDS) suffers from leakage, diversion, and server or biometric failures, denying ration to genuine beneficiaries. Current digital systems lack transparency and inclusivity, leaving citizens unable to track stock or report grievances. These issues weaken food security and trust in government programs.


### Solution

Ration Transparency 2.0 is a citizen-centric platform that provides real-time stock updates, offline  transaction recording, and multi-mode authentication via app and IVR. It empowers beneficiaries with digital receipts, grievance reporting, and ensures transparency at every step, reducing leakage and ensuring fair distribution of food grains.

---

# Table of Contents

1. [Introduction](#anajsuraksha)
2. [Table Of Contents](#table-of-contents)
3. [Features](#key-features-of-ration-transparency-20)
4. [Installation](#installation)
5. [Deployment](#deployment)

---

# Key Features of Ration Transparency 2.0


1. **Real-Time Stock Tracking**

> Citizens can check the availability of grains, sugar, and kerosene at every Fair Price Shop - The app fetches live data from ePoS machines and updates the stock status instantly. This prevents misinformation from shopkeepers and ensures beneficiaries know exactly what is available before visiting the FPS.


2. Offline-First Operation

> Transactions are recorded locally when the server is down and sync automatically once connectivity will come - Even during network outages, the system ensures accurate record-keeping, preventing dealers from exploiting downtime to misreport stock or deny ration.


3. Multi-Mode Authentication

> Supports Aadhaar OTP, PIN, QR code, and alongside biometric verification - This ensures no beneficiary is denied ration due to fingerprint mismatches or technical failures, increasing trust and reducing errors in authentication.


4. IVR and Voice Support.

> A toll-free IVR system provides voice-based updates for non-smartphone or low-literacy users like village people - Beneficiaries can call the system to check their entitlement, stock availability, and transaction status, making the system accessible to all, including rural populations.


5. Digital Receipts and Grievance Redressal

> Beneficiaries receive digital receipts for every transaction and can report issues or provide feedback - Digital  proof of transaction increases accountability of shopkeepers and provides a direct channel for citizens to report irregularities, also reducing corruption.


6. Analytics Dashboard for Policymakers

> Authorities can monitor supply-demand patterns, detect uneven patterns, and prevent stock diversion- Data-driven insights allow governments to identify problem areas, optimize distribution, and make policy decisions to reduce leakage and inefficiency.


7. Citizen Empowerment Features

> Includes FPS rating and geo-tagged tracking of stock deliveries - Citizens can evaluate shops and view location-based supply updates, promoting transparency and they can also view their updates and other schemes anytime and anywhere.

---

# Installation

1. **Clone the repository:**
```
git clone https://github.com/CoderHarshDew/AnajSuraksha.git
cd AnajSuraksha

```

---
# Deployment

Ration Transparency 2.0 is designed for easy deployment and integration with the existing AePDS and ePoS infrastructure. The Deployment involves the following steps:


1. Backend Setup: The cloud-based server is hosted on government-approved platforms (AWS/GCP), connected securely with state-level AePDS servers. APIs are configured to fetch real-time FPS stock and transaction data.


2. Application Deployment: The mobile app is built using a hybrid framework and can be installed on Android and iOS devices. Updates are pushed remotely to ensure all users have the latest version.


3. IVR Integration: A toll-free IVR system is connected via telecom APIs, allowing beneficiaries without smartphones to access stock updates and grievance reporting.


4. Offline Configuration: ePoS devices and local app instances are configured to store transactions locally during network outages. The system automatically sync with the cloud server once connectivity is restored.
