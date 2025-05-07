# AIMaL
# AIMAL – Artificially Intelligent Malware Launcher

**AIMAL** is a red team simulation framework built for testing modern malware evasion techniques against AV, EDR, and IDS. It supports modular evasion techniques like Process Herpaderping, Process Hollowing, Thread Hijacking, and Process Ghosting, combined with AI-assisted mutation logic, stealthy payloads, and real-time feedback adaptation.

AIMAL integrates with the OpenAI API to dynamically suggest evasive actions based on simulated alerts (e.g., behavioral or signature detection). It can autonomously apply countermeasures like shellcode polymorphism, PPID spoofing, syscall chain mutation, and noise injection — transforming detection into adaptation.

> **Current payloads:**  
> - Stealth AES-encrypted reverse shell  
> - Silent ransomware variant (*in development*)  
> - More to come...

### 🎯 Screenshot – Real-Time Detection Feedback + Mutation

![AIMAL Screenshot](AIMaL.jpg)

> _Full source code and public release coming soon. For DEF CON Demo Labs use only._

🎥 [Watch Bypassing Demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7325447443276292096/)

---
📚 **Research Focus**: Offensive AI, evasive malware loaders, shellcode polymorphism, and stealth system injection.  
📅 **Demoed at**: DEF CON Demo Labs 2025 (submission pending)
