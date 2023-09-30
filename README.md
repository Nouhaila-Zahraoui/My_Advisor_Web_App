# my_Advisor_web_application

my_Advisor_web_application is a web application that allows users to share their opinions and reviews about services in a city they plan to visit. 
It provides a platform for users to get valuable insights and recommendations from others, making their travel planning process easier.

## Features

- **User Registration and Authentication**: Users can create accounts, log in, and manage their profiles.

- **Service Reviews**: Users can browse and search for services, read reviews, and leave their own reviews and ratings.

- **City Selection**: Users can select a city to explore the services and reviews specific to that location. 

- **Chat Box: Users can communicate privately in real-time using the chat box feature.

-**Comments Section: Users can share their honest opinions about a particular service through comments.

-**Admin Dashboard: The administration has the ability to manage users, services, and cities (add, edit, delete), as well as access a graphical visualization of data.

- **Responsive Design**: The application is responsive and works seamlessly on various devices, including desktops, tablets, and mobile phones.

## Technologies Used


- **Frontend**: Developed using React.js, a popular JavaScript library for building user interfaces.

- **Backend**: Built with Spring Boot, a Java-based framework for creating robust and scalable web applications.

- **Database**: MongoDB is used as the database to store user data, service information, and reviews.

## Getting Started

To get started with my_Advisor_web_application on your local machine, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/my_Advisor_web_application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd my_Advisor_web_application
   ```

3. Install the frontend dependencies:

   ```bash
   cd frontend
   npm install
   ```

4. Install the backend dependencies:

   ```bash
   cd ../backend
   mvn install
   ```

5. Create a MongoDB database and update the database configuration in the `application.properties` file.

6. Start the backend server:

   ```bash
   mvn spring-boot:run
   ```

7. Start the frontend development server:

   ```bash
   cd ../frontend
   npm start
   ```

8. Access the application in your web browser at `http://localhost:3000`.

## Contributing

We welcome contributions from the community. If you'd like to contribute to this project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

For questions or feedback, you can reach us at [zehraoui.1998@@gmail.com.

---

Feel free to customize this README template to fit your project's specific details and requirements. Additionally, consider adding sections for deployment instructions, troubleshooting, or any other relevant information that can help users and contributors understand and use your application effectively.
