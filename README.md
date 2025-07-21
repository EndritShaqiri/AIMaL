# AIMaL — Artificially Intelligent Malware Launcher

![AIMaL ASCII Logo](https://raw.githubusercontent.com/EndritShaqiri/AIMaL/main/aimal_logo.png)

**AIMaL (Artificially Intelligent Malware Launcher)** is a modular red team evasion framework designed to simulate advanced malware behavior that adapts in real time using AI.

Developed for adversarial simulation, stealth malware R&D, and AV/EDR evasion testing, AIMaL uses OpenAI’s API to automatically rewrite its own evasion techniques (ET) and execution paths (XT) based on the type of detection encountered — signature-based or behavioral-based.

---

## 🔥 Live Demo at DEF CON 33

**Red Team Village (TACTICS) & Demo Labs Presenter**  
Join us for a hands-on walkthrough of AIMaL’s architecture and see how AI rewrites malware in real-time to bypass modern AV/EDR solutions.

---

## ⚙️ Key Features

- **Evasion Techniques (ET):**  
  - Process Hollowing  
  - Process Ghosting  
  - Process Herpaderping  
  - AI-generated custom ETs

- **Execution Techniques (XT):**  
  - APC (Asynchronous Procedure Calls)  
  - Thread Hijacking

- **Payloads:**  
  - AES-encrypted Reverse Shell (C++)  
  - Ransomware (under development)  
  - Future: Rootkit module

- **AI Self-Patch Mode:**  
  - Uses OpenAI API to rewrite logic based on AV feedback  
  - Signature detection → adds junk functions, polymorphs shellcode  
  - Behavioral detection → rewrites ET or builds new one

- **Advanced Stealth Features:**  
  - PPID Spoofing  
  - Hell’s Gate / Heaven’s Gate syscall mutation  
  - Fake API calls, random delays, AMSI/ETW patching  
  - Polymorphic rebuilds per execution

---

## 🧠 Why AIMaL?

AIMaL simulates an intelligent threat that mutates on the fly — just like real-world APT malware.  
It’s ideal for:
- Red Team drills
- AV/EDR stress testing
- Research into AI-augmented malware and detection evasion

---

🧑‍💻 Authors
Endrit Shaqiri
📧 endritshaqiri2016@gmail.com
🌐 LinkedIn

Natyra Shaqiri
📧 natyrashaqiri@smccme.edu
🌐 LinkedIn

