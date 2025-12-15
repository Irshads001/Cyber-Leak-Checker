DataGuard - Identity Breach Checker
🛡️"Security is not a product, it's a process."

About The Project
DataGuard is a powerful, real-time security awareness tool designed to help users verify if their personal information (Email, Phone, Username) has been compromised in recent public data breaches.
Built with a cyber-security aesthetic, it connects to a secure Firebase Firestore database to cross-reference user queries against millions of leaked records without compromising user privacy.

Live Preview
(Add a screenshot of your website here)

Key Features
1.Secure Search Architecture: Queries are processed securely; we do not store or log user search inputs.
2.Real-time Database: Powered by Google Firebase Firestore for millisecond-latency results.
3.Fully Responsive Cyber UI: A "Dark Mode" hacker-themed interface built with React and Tailwind CSS.
4.Instant Alerts: Immediate feedback on data exposure sources (e.g., Instagram, Facebook breaches).
5.Actionable Advice: Provides security recommendations if a breach is detected.

Technologies Used
Frontend: HTML5, React.js (via CDN), Tailwind CSS
Backend: Firebase Firestore (NoSQL Database)
Icons: Lucide React (SVG)
Deployment: GitHub Pages

How It Works
The Engine: The app connects to a read-only Firestore collection containing hashed/masked breach data.
The Search: When a user enters an identifier, the system queries the database.
The Result: *Safe: No records found.
Breached: Displays the source of the leak and compromised fields (e.g., Password, IP).

⚠️ Disclaimer
For Educational & Security Awareness Purposes Only.
This tool is designed to help individuals protect their digital identity by alerting them to potential risks. The dataset used in this project consists of publicly available information from known data breaches. The creator of this project does not condone illegal activities or the misuse of personal data.

Setup for Developers:
If you want to run this locally:
Clone the repo:
git clone [https://github.com/irshads001/Cyber-Leak-Cheker.git](https://github.com/irshads001/Cyber-Leak-Cheker.git)

Open index.html in your browser.
Note: You must provide your own Firebase API Keys in the configuration section.
<p align="center">
Made with google gemini and by <strong>IRSHAD</strong>
</p>
