# trapnet
Design and Implementation of a Honeypot System to Detect and Analyze Malicious Activity in a Web Application
This project involves the creation of a Honeypot-based detection and analysis system tailored to simulate a real, vulnerable web application environment. It aims to detect, log, and analyze malicious activity while also sending real-time alerts via email when suspicious behavior is detected.

The honeypot deceives attackers by presenting fake login forms, input fields, and hidden endpoints designed to appear exploitable. Once an attacker interacts with these, the system logs their actions—such as SQL injection attempts, unauthorized URL access, or brute-force login tries—and immediately sends a notification email to the administrator for timely action.

Technologies Used:
Frontend: HTML, CSS, JavaScript (for UI and traps)

Backend: Python with Flask

Email Alerts: Python smtplib.

Database: SQLite/MySQL for attack logs

Security Tools: Wireshark

Data Analysis: Python 

Email Alert Feature:
Automatically detects suspicious activities like:

SQL injection patterns

Unusual POST/GET requests

Suspicious headers or payloads

Brute-force login attempts

Sends an email alert to the administrator with:

Attacker’s IP address

Timestamp

Type of attack or payload detected

Affected URL or endpoint

This helps ensure real-time awareness and allows quick action against potential breaches or scans.
