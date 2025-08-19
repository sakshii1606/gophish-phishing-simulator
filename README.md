![gophish logo](https://raw.github.com/gophish/gophish/master/static/images/gophish_purple.png)

Gophish
=======

![Build Status](https://github.com/gophish/gophish/workflows/CI/badge.svg) [![GoDoc](https://godoc.org/github.com/gophish/gophish?status.svg)](https://godoc.org/github.com/gophish/gophish)

Gophish: Open-Source Phishing Toolkit

[Gophish](https://getgophish.com) is an open-source phishing toolkit designed for businesses and penetration testers. It provides the ability to quickly and easily setup and execute phishing engagements and security awareness training.

### Install

Installation of Gophish is dead-simple - just download and extract the zip containing the [release for your system](https://github.com/gophish/gophish/releases/), and run the binary. Gophish has binary releases for Windows, Mac, and Linux platforms.

### Building From Source
**If you are building from source, please note that Gophish requires Go v1.10 or above!**

To build Gophish from source, simply run ```go install github.com/gophish/gophish@latest``` and ```cd``` into the project source directory. Then, run ```go build```. After this, you should have a binary called ```gophish``` in the current directory.

### Docker
You can also use Gophish via the official Docker container [here](https://hub.docker.com/r/gophish/gophish/).

### Setup
After running the Gophish binary, open an Internet browser to https://localhost:3333 and login with the default username and password listed in the log output.
e.g.
```
time="2020-07-29T01:24:08Z" level=info msg="Please login with the username admin and the password 4304d5255378177d"
```

Releases of Gophish prior to v0.10.1 have a default username of `admin` and password of `gophish`.

### Documentation

Documentation can be found on our [site](http://getgophish.com/documentation). Find something missing? Let us know by filing an issue!

### Issues

Find a bug? Want more features? Find something missing in the documentation? Let us know! Please don't hesitate to [file an issue](https://github.com/gophish/gophish/issues/new) and we'll get right on it.

### License
```
Gophish - Open-Source Phishing Framework

The MIT License (MIT)

Copyright (c) 2013 - 2020 Jordan Wright

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software ("Gophish Community Edition") and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
# Gophish Phishing Simulator (Kali Linux + Mailtrap)

A hands-on phishing simulation project demonstrating safe phishing campaigns using **Gophish** on Kali Linux with **Mailtrap**.

---

## 🛠️ Tools & Technologies
- **Kali Linux** – platform for running Gophish  
- **Gophish** – open-source phishing framework  
- **Mailtrap** – safe SMTP server for testing emails  
- **Git & GitHub** – version control and project showcase  

---

## 📋 Project Overview
This project simulates a phishing attack in a safe, controlled environment. The main steps performed:

1. Installed and configured **Gophish** on Kali Linux  
2. Set up **Mailtrap** as a sending profile (SMTP)  
3. Created phishing **email templates** and **landing pages**  
4. Ran a test phishing campaign  
5. Collected results in CSV format and captured screenshots  

> ⚠️ **Note:** This project is for educational purposes only. Do not use it against real users.

---

## 📁 Files Included
- `README.md` – project explanation  
- `results.csv` – phishing campaign results  
- `screenshots/` – campaign UI and email screenshots  
- `docs/` – project notes, configuration explanations  
- `license` – project license (if applicable)  

---

## 📸 Screenshots
_Add some images of your Gophish dashboard, campaign results, or email templates here:_  

![Gophish Dashboard](screenshots/dashboard.png)  
![Campaign Results](screenshots/results.png)  

---

## 🔗 GitHub Repository
[View the project on GitHub](https://github.com/sakshii1606/gophish-phishing-simulator)

---

## 👩‍💻 Author
Sakshi Phadtare  
Cybersecurity Enthusiast | SOC Analyst in training  

