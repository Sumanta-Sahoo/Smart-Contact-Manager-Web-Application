# Smart Contact Manager (SCM)

This repository contains the Smart Contact Manager (SCM) web application, designed to manage and interact with contact information efficiently. Built using **ReactJS** for the front end and **MySQL** for the database, the backend leverages the **Spring Framework** (Spring IoC DI,SpringBoot, Spring MVC, Spring Security) and **Maven** for project management. The application follows design patterns to ensure robust, maintainable code.

## Features

1. **Ask Al**: Integrated assistance to help users navigate and utilize the application efficiently.
2. **Verify Account**: Account verification through an email verification link.
3. **User Signup with Google and GitHub**: Seamless user registration using Google and GitHub accounts.
4. **Add Contacts with Picture**: Users can add new contacts along with their pictures.
5. **Upload Contact Picture to Cloud**: Contact pictures are securely uploaded to cloud services like AWS or Cloudinary.
6. **View All Contacts**: Users can view a list of all their contacts.
7. **View Contact Details**: Detailed view of individual contacts.
8. **Compose and Send Email**: Users can compose and send emails directly from SCM.
9. **Email with Attachments**: Emails can include text and attachments.
10. **Update Contact**: Edit and update contact information.
11. **Delete Contact**: Remove contacts from the database.
12. **Search Contact**: Easily search for contacts using a search bar.
13. **Pagination**: Efficiently navigate through large lists of contacts with pagination.
14. **Export to Excel**: Export contact data to an Excel file for easy sharing and backup.
15. **Mark Favorite Contacts**: Mark and manage favorite contacts for quick access.
16. **Profile Management**: View and edit own profile details.

## Technologies Used

- **Frontend**: ReactJS
- **Backend**: Spring Framework (Spring IoC DI, Spring MVC, Spring Security)
- **Database**: MySQL
- **Cloud Storage**: AWS, Cloudinary
- **Build Tool**: Maven

## Getting Started

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/scm-web-app.git
   ```

2. **Navigate to the Project Directory**:
   ```sh
   cd scm-web-app
   ```

3. **Install Dependencies**:
   ```sh
   mvn clean install
   ```

4. **Set Up Database**:
   - Ensure MySQL is installed and running.
   - Create a database and update the application properties with the database credentials.

5. **Run the Application**:
   ```sh
   mvn spring-boot:run
   ```

6. **Access the Application**:
   Open your browser and navigate to `http://localhost:8080`.

## Contributing

We welcome contributions! Please fork the repository and submit a pull request for review.

## License

This project is licensed under the MIT License.

For more information and detailed documentation, please refer to the respective sections in the repository.
