Job Portal Web App (Spring Boot)
A simple and functional Job Portal Web Application built using Spring Boot.
This project provides REST APIs to post jobs, view jobs, update jobs, delete jobs, and manage job data. It is designed as a backend-only application that can be connected to any UI later.
⸻
✅ Features
• Create job postings
• Update job postings
• Delete job postings
• View all job listings
• View job details by ID
• Search jobs by title, location, and company
• Layered architecture (Controller → Service → Repository → Entity)
• Validation for job fields
• Global exception handling
• Clean and organized Spring Boot structure
Job Portal Web App (Spring Boot)
A simple and functional Job Portal Web Application built using Spring Boot.
This project provides REST APIs to post jobs, view jobs, update jobs, delete jobs, and manage job data. It is designed as a backend-only application that can be connected to any UI later.
⸻
✅ Features
• Create job postings
• Update job postings
• Delete job postings
• View all job listings
• View job details by ID
• Search jobs by title, location, and company
• Layered architecture (Controller → Service → Repository → Entity)
• Validation for job fields
• Global exception handling
• Clean and organized Spring Boot structure

Project Structure : 
src/main/java
└── com.example.jobportal
      ├── controller       → Handles REST endpoints
      ├── service          → Business logic
      ├── repository       → I have used the ArrayLists for storing the Jobs ( You can use JPARepository)
      ├── model/entity     → Job entity class
      └── JobPortalApplication.java
src/main/resources
├── application.properties
└── data.sql / schema.sql (optional for sample data)

🔧 Sample REST Endpoints
->Create a Job
->Get All Jobs
->Get Job by ID
->Update Job
->Delete Job
->Search Jobs

🧩 Technologies Used
• Spring Boot
• Spring Web (REST APIs)
• Spring Data JPA
• Hibernate
• Java 8+

🚀 How to Run
1. Clone the repository  :  git clone https://github.com/Vamsijut/job-portal-webapp.git
2. Open the project in any IDE (IntelliJ/Eclipse/Spring Tool Suite)
3. Run the main class: JobPortalApplication.java
4. Application runs on : http://localhost:8080


🧪 Optional Enhancements
• Add category-based filtering
• Add pagination for job listings
• Add user roles (Admin/Employer)
• Add DTO + ModelMapper
• Connect with React/Angular UI later

📄 License
MIT License
