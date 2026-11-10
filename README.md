# VERUM

## Team
- Yeva Yefimova
- Anastasiia Dziuba

## About the Project
VERUM is a web-based platform designed to help people recognize and avoid phishing attacks. No registration is required to access educational materials, check suspicious links, or take basic quizzes
The platform also provides a dedicated section for companies. Company administrators can register their organization, create employee accounts, and launch phishing simulation campaigns. They can then monitor employee responses and see who
interacted with simulated phishing emails.
Our target audience includes small and medium-sized businesses that do not have their own cybersecurity departments, as well as individuals who want to learn how to distinguish phishing emails from legitimate ones.

## User Roles
- **Guest (no registration required):** Can read educational materials about phishing, check suspicious links, and take basic quizzes.
- **Employee:** Can practice in a simulated inbox, earn points and badges, track personal results, and report suspicious emails.
- **Company Administrator:** Can register a company, create employee accounts, select email templates, launch simulation campaigns, and view statistics and risk scores. Has access only to their company's data.
- **Platform Administrator:** Manages registered companies (including the ability to suspend them), adds educational materials and email templates, and configures global platform settings.

## Core Features
**Available to Everyone (No Registration Required):**
- Educational articles about phishing with interactive mini-quizzes
- Suspicious link checker with explanations of potential security risks
- Basic knowledge tests
**Company Features:**
- Company registration and employee account management
- **Mode A – Realistic Phishing Simulations:** The administrator selects an email template and adds campaign recipients manually or generates fake recipients for testing. Each recipient receives an email containing a unique tracking link.
- **Mode B – Training Inbox:** Employees review emails and decide whether each one is legitimate or a phishing attempt. Correct answers earn points.
- **Campaign Statistics:** Tracks the number of emails sent, who clicked a link, who reported a phishing attempt, who did not respond, and employee training results.
- **Risk Scoring:** Calculates an individual risk score for each employee, as well as an overall company risk level (low, medium, or high).

## Key Features & Project Highlights
- **Two Training Modes:** Combines realistic phishing simulations with click tracking through unique tokens and an interactive training inbox with a points-based system.
- **Risk Scoring System:** Combines results from both training modes. Realistic simulation results carry more weight because they better reflect real-world behavior, while training inbox results carry less weight since phishing attempts are easier to
recognize when users know they are taking a test. If a company uses only one training mode, the risk score is calculated based solely on that mode.
- **Link Analysis:** Combines custom security checks (lookalike domains, URL shorteners, suspicious domains, etc.) with integrations with third-party APIs.
- **Data Isolation:** Each company can access only its own data.


> All simulations are conducted with participants' knowledge and use test inboxes only. We do not collect passwords or any other real user credentials
