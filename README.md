# HireBridge - Modern Job Portal

HireBridge is a comprehensive, full-stack job portal application designed to bridge the gap between talented job seekers and leading employers. Built with a robust Spring Boot backend and a dynamic, responsive frontend, HireBridge offers a seamless experience for finding and posting jobs.

## 🚀 Features

- **User Authentication**: Secure signup and login for both job seekers and employers.
- **Job Search & Discovery**: Browse jobs by categories, location, and keywords.
- **Job Details**: Comprehensive job descriptions with application links.
- **Employer Dashboard**: Post and manage job listings effortlessly.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop viewing.
- **Email Notifications**: Integrated email service for application updates and communication.
- **Contact System**: Built-in contact form for user support and inquiries.

## 🛠️ Tech Stack

### Backend
- **Framework**: Spring Boot 3.4.4
- **Language**: Java 21
- **Database**: PostgreSQL (Production), H2 (Development)
- **Data Access**: Spring Data JPA
- **Communication**: Spring Boot Mail (JavaMailSender)

### Frontend
- **Languages**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS & Bootstrap
- **Libraries**: Owl Carousel, Waypoints, Animate.css, WOW.js

## 📂 Project Structure

```text
HireBridge/
├── src/main/java/          # Backend Java source code
├── src/main/resources/     # Configuration and static assets
│   ├── static/             # HTML, CSS, JS, and Images
│   └── application.properties # Application settings
├── pom.xml                 # Maven dependencies
└── uploads/                # User uploaded documents (ignored by git)
```

## ⚙️ Setup & Installation

### Prerequisites
- JDK 21 or higher
- Apache Maven
- PostgreSQL (optional, defaults to H2)

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/MOHAMMEDAMAN8504/HireBridge.git
   cd HireBridge
   ```

2. **Configure Database**:
   Update `src/main/resources/application.properties` with your database credentials if you're not using the default H2 configuration.

3. **Build the project**:
   ```bash
   mvn clean install
   ```

4. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

5. **Access the portal**:
   Open your browser and navigate to `http://localhost:8080`.

Built by [Mohammed Aman](https://github.com/MOHAMMEDAMAN8504)
