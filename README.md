 𝓞𝓬𝓮𝓪𝓷𝓼 𝓸𝓯 𝓜𝓮𝓻𝓬𝔂

Oceans Of Mercy is an ASP.NET MVC application designed to manage donations, users, and drivers efficiently. The project integrates Firebase for authentication and messaging, 
ensuring secure user management and real-time notifications.

Features

User Management: Register, authenticate, and manage users with Firebase Authentication.
Donation Tracking: Users can donate items, track donation history, and search donations by amount and donor name.
Driver Management: Add and update driver details, including their availability status.
News & Articles: Create and manage news articles with image uploads.

Firebase Integration:
-	Authentication services for secure user login.
-	Firestore database for real-time data storage.
-	Firebase Cloud Messaging (FCM) for notifications.
Dashboard & Analytics: View key insights and analytics from donations and user activity.


Installation & Setup
Prerequisites
- Visual Studio
- .NET Core SDK
- Firebase account (for authentication and messaging services)
- SQL Server (or an equivalent database solution)

Steps to Run the Project

1.	Clone the Repository
2.	git clone https://github.com/your-repository/Oceans-of-Mercy-MVC.git
cd Oceans-of-Mercy-MVC
3.	Open in Visual Studio
o	Open OceansOFMercyy.sln in Visual Studio.
4.	Configure Firebase
o	Update FirebaseService.cs with your Firebase credentials.
o	Ensure Firebase authentication and Firestore rules are properly set up.
5.	Database Configuration
o	Update appsettings.json with your SQL Server connection string.
o	Run database migrations (if applicable).
6.	Run the Application
-	Press F5 or use dotnet run to start the project.
-	Access the dashboard via http://localhost:5000 (or the configured port).

