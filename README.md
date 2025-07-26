# GoPWNIt - CTF as a Service & Cybersecurity Learning Platform
---

## 🛡️ Overview

**GoPWNIt** is a cutting-edge **CTF (Capture The Flag) as a Service** and **cybersecurity education platform** designed for learners, professionals, educators, and cybersecurity enthusiasts. It provides an all-in-one ecosystem for **hosting**, **learning**, and **competing** in cybersecurity challenges—built with modern security and scalability in mind.

Our mission is to **gamify cybersecurity learning** while maintaining **enterprise-grade session and authentication security**.

---

## 🔐 Key Security Features

### ✅ Single Session Enforcement
- Enforces one active session per user across all devices.
- Prevents simultaneous logins to preserve session integrity.

### 🚫 Concurrent Session Bypass Prevention
- Strong session validation: prevents session cookie reuse to bypass authentication.

### 🔑 Asymmetric Encryption for Authentication
- **Login and signup operations are secured using asymmetric cryptography (RSA-based)**.
- Sensitive credentials are encrypted client-side using a public key, and decrypted only on the server with a private key.
- Mitigates risks of credential interception or token compromise.

---

## 📘 Platform Highlights

### 🎓 Cybersecurity Learning Engine

- **Course-Based Curriculum**  
  Courses are divided into modules and further into chapters to provide structured, incremental learning.

- **Dynamic Unlock System**  
  Chapters unlock based on user progression and chapter completion.

- **In-Chapter Interactivity**  
  Questions, practical challenges, and assessments reinforce learning at every step.

- **Gamified Experience**  
  Earn points and achievements as you progress.

### 🏁 CTF Hosting & Challenge Management

- **User-Generated CTF Seasons**  
  Anyone can create and host their own CTF competitions with full administrative control.

- **Challenge Lifecycle Tools**  
  - Create, draft, edit, and publish challenges  
  - Categorize by topic, difficulty, and type  
  - Add hints, timers, scoring logic

- **Full Season Control Panel**  
  - Open/close registrations  
  - Publish/unpublish CTF seasons  
  - Ban or unban users  
  - Monitor submissions and scores in real-time

---

## 🧠 Learning Content Hierarchy

```text
Course
 └── Module
      └── Chapter
           ├── Lessons
           ├── Practical Questions
           └── Unlock Conditions (Based on Completion Criteria)

