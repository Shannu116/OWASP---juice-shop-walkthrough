# OWASP-juice-shop-walkthrough
## Project Objective:
The objective of the project was to conduct a walkthrough of the OWASP Juice Shop, a deliberately insecure web application, using tools like Kali Linux and Burp Suite to perform penetration testing. The goal was to identify and exploit security vulnerabilities following the OWASP Top 10 guidelines.

## Tools
Kali Linux: Kali Linux is a powerful penetration testing distribution widely used by cybersecurity professionals. It comes pre-installed with numerous tools for various security - assessments, including network analysis, vulnerability assessment, and exploitation.

Burp Suite: Burp Suite is a leading toolkit for web application security testing. It provides a comprehensive platform for manual testing and automated scanning of web applications, helping identify security vulnerabilities such as SQL injection, cross-site scripting (XSS), and more.

Nikto: Nikto is an open-source web server scanner designed to identify potential security issues and vulnerabilities. It performs comprehensive tests against web servers for dangerous files, outdated software, misconfigurations, and other common security problems. Nikto is widely used in reconnaissance phases to gather valuable information about a target system.

Nmap: Nmap (Network Mapper) is a powerful network scanning and reconnaissance tool used by cybersecurity professionals. It helps in discovering hosts, services, open ports, and potential vulnerabilities on a network. Nmap supports a wide range of scanning techniques, making it ideal for network inventory, security auditing, and penetration testing.

## Skills Gained

Web Application Security Testing: Performing a walkthrough of the OWASP Juice Shop involved gaining hands-on experience in identifying and exploiting common web application vulnerabilities, such as injection flaws, broken authentication, sensitive data exposure, and more. This skill is crucial for cybersecurity professionals to understand the methods attackers use to compromise web applications.

Burp Suite Proficiency: Through this project, proficiency in using Burp Suite for web application security testing was developed. This includes configuring proxy settings, intercepting and modifying HTTP requests, analyzing responses, and utilizing various features such as the repeater and Intruder modules. Mastering tools like Burp Suite is essential for effective and efficient vulnerability assessment and exploitation.

Reporting and Documentation: Effective communication of findings is vital in cybersecurity. This project provided an opportunity to practice documenting discovered vulnerabilities, including their impact and remediation recommendations. Creating clear and concise reports is essential for stakeholders to understand and address security issues promptly.

## Installation

to install the juice-shop useing this command
### sudo git clone https://github.com/juice-shop/juice-shop.git

## Usage

After cloning the repo go to the cerated directory and install the dependencies.

npm install
npm start
after browse to this page http://localhost:3000/#/

there you can see the web page and you can start according to the walkthrough

