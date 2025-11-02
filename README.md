# Applied-Programming-POE
The Gift of the Givers Foundation Web Application

Student: ST10364877 – Gudani Phumudzo Makwarela
Project: Disaster Alleviation Foundation Web Application
Technology Stack: C#, ASP.NET Core MVC, Azure SQL Database, Azure DevOps


Introduction

This project implements a web application for the Gift of the Givers Foundation to manage disaster relief operations. It enables secure user registration/login, disaster reporting, resource donation management, and volunteer coordination. Azure DevOps is used for version control and automated CI/CD pipelines.



Features
	•	User Registration and Login: Secure authentication with hashed passwords.
	•	Disaster Incident Reporting: Users can submit detailed reports with type, location, and description.
	•	Resource Donation Management: Track and manage donations with proper classification.
	•	Volunteer Management: Register volunteers, assign tasks, and monitor participation.
	•	Version Control: Source code maintained in Azure Repos following Git Flow.
	•	Automated CI/CD: Azure Pipelines configured for build, test, and deployment.



Project Structure
	•	Controllers: Handle application logic.
	•	Models: Define data models and view models.
	•	Views: Razor pages for user interaction.
	•	Migrations: Database schema setup.
	•	Program.cs & appsettings.json: Application configuration.



Database
	•	Azure SQL Database stores all entities: Users, Donations, Volunteers, Incident Reports.
	•	DbContext manages database operations and relationships.
	•	Migrations validate that the database schema exists and is applied correctly.



Build and Deployment
	•	Azure Pipelines automates builds, tests, and deployments.
	•	Pipeline Workflow:
	1.	Restore dependencies
	2.	Build solution
	3.	Run unit tests
	4.	Publish artifacts
	5.	Deploy to Azure App Service
	•	Branch Triggers: develop → Test environment, main → Production environment



Testing
	•	Unit & Integration Testing: Ensures correctness of backend logic and module interactions.
	•	Load & Stress Testing: Evaluates performance under high traffic and extreme conditions.
	•	UI Testing: Verifies functionality of forms and navigation.
	•	Usability Testing: Users provided feedback on navigation, clarity, and overall experience.



Links
	•	Azure DevOps: https://dev.azure.com/ST10364877/ST10364877_Gift%20Of%20The%20Givers/_sprints/backlog/ST10364877_Gift%20Of%20The%20Givers%20Team/ST10364877_Gift%20Of%20The%20Givers/Sprint%203
	•	Git Repository: 

⸻

Conclusion

The project successfully implements a functional prototype of the Disaster Alleviation Foundation Web Application. It provides secure authentication, disaster reporting, donation tracking, and volunteer management. Integration with Azure Repos and Azure Pipelines ensures robust version control, collaboration, and automated deployment, providing a strong foundation for further development.
