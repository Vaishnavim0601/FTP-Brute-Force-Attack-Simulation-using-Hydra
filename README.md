# 📡 FTP Brute Force Attack Simulation using Hydra

## 📌 Overview

This project demonstrates brute force attacks using Hydra against a vulnerable Metasploitable machine in a controlled lab environment to test password strength and identify security weaknesses.

## 🎯 Objectives

* Simulate brute force attacks using Hydra
* Use Metasploitable as the vulnerable victim machine
* Test weak credentials
* Analyze security risks

## 🛠️ Tools & Technologies

* Hydra
* Metasploitable
* Kali Linux

## ⚙️ Methodology

1. Set up Metasploitable as the target machine
2. Prepared username and password wordlists
3. Executed Hydra brute force attack on the FTP service
4. Monitored attack behavior and captured results

## ▶️ Sample Command

```bash id="k9p2xz"
hydra -l username -P passwords.txt ftp://<target-ip>
```

## 📊 Results

* Successfully demonstrated brute force attack
* Identified weak credentials
* Highlighted risks of poor password policies

## 🔐 Key Learnings

* Password attack techniques
* Working with vulnerable machines (Metasploitable)
* Importance of strong authentication

## ⚠️ Disclaimer

This project was conducted in a controlled environment strictly for educational purposes.
