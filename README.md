[README for ScholarNet.docx](https://github.com/user-attachments/files/17814332/README.for.ScholarNet.docx)

README for ScholarNet

ScholarNet is an educational web application designed to provide students with easy access to grade-specific learning materials in PDF format. The platform ensures a user-friendly experience for students, allowing them to view and download study materials tailored to their academic needs. Firebase Authentication powers secure user logins, while role-based access ensures only authorized administrators can manage resources. These administrators have access to a dedicated dashboard where they can upload, edit, and delete educational content, ensuring the platform remains up to date with relevant resources. Firebase Firestore is utilized for efficient and real-time data storage, making changes instantly accessible to all users.
Built with scalability and future growth in mind, ScholarNet offers a streamlined solution for digital education resource management. Its architecture supports potential enhancements such as the addition of multimedia content, advanced analytics, and interactive features to further enrich the learning experience. By bridging the gap between educators and students, ScholarNet provides a secure and efficient platform that simplifies the distribution and management of educational materials, helping students focus on their academic journey.

Features
1.	User Authentication:
-	Students and administrators can securely log in to the platform using Firebase Authentication.

2.	Role-Based Access:
-	Students have access to materials tailored to their grade level.
-	Administrators have additional privileges to manage files and resources within the system.

3.	File Management (Admin Only):
-	Administrators can upload new educational materials, edit file details, and remove outdated or irrelevant content.

4.	Material Display:
-	Students can view a list of materials filtered by their grade level and download the relevant files in PDF format.

5.	User-Friendly Interface:
-	The platform features a simple and intuitive design, ensuring a seamless experience for both students and administrators.

How to Use ScholarNet

For Students:

1.	Sign In:
-	Open the ScholarNet website and sign in using your email and password.
-	If you don’t have an account, ask an administrator to create one for you.

3.	View Materials:
-	Once logged in, you’ll be redirected to your dashboard.
-	Browse the list of educational materials tailored to your grade level.

4.	Download Files:
-	Click on a material to download the corresponding PDF file to your device.

For Administrators:

1.	Sign In:
-	Log in with your admin credentials. Ensure your role is set as "admin" in the Firestore database.

2.	Manage Files:
-	Access the admin dashboard to add, edit, or delete files.
-	To upload a file: 

 	= Fill in the title and description fields.

 	= Attach the file in PDF format.

 	= Click "Add Data" to save it in the database.
-	To edit or delete an existing file, use the corresponding buttons next to each entry.

3.	User Management:
-	You can also manage users (if implemented in your database setup) via Firebase Firestore.

Technology Stack
-	Frontend: HTML, CSS, and JavaScript
-	Backend: Firebase Authentication and Firestore
-	Hosting: Firebase Hosting

Future Plans
ScholarNet aims to expand its feature set with interactive quizzes tailored to each grade level, helping students test their knowledge, track their progress, add a teacher dashboard and allow for student-teacher interaction online.

