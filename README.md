# FormBot

**FormBot** is an automated backend system built with Spring Boot. It allows sending personalized Google Forms links via WhatsApp (Twilio), reading responses from Google Sheets, generating monthly reports in PDF format, and sending them via email.

---

## 📌 Features

- WhatsApp integration using Twilio
- Google Sheets API integration for reading form responses
- PDF report generation (monthly)
- Email delivery via SMTP or SendGrid
- PostgreSQL database
- Spring Scheduler for automated tasks
- Clean architecture with layered package structure

---

## 🛠 Technologies Used

- Java 21
- Spring Boot 3.4.5
- Spring Data JPA
- Spring Validation
- Spring Mail
- PostgreSQL
- Lombok
- Maven
- Docker & Docker Compose

---

## 🚀 Running Locally

### Prerequisites
- Java 21 (JDK)
- Maven 3.9+
- PostgreSQL running locally
- Git

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/KauaCorreaArruda/formbot.git
cd formbot
