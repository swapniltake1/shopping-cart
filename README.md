# Shopping Cart Project

Welcome to the Shopping Cart project repository! This project is aimed at providing a seamless shopping experience for both local users and administrators. The project consists of two main services: one for local users to purchase items from the site, and another service for administrators to manage items and perform administrative tasks.

## Features

- **Local User Service (Port 8080):** This service allows local users to browse products, add items to their cart, and proceed with the checkout process.
- **Admin Service (Port 8090):** Administrators can access this service to add new products, update existing ones, manage inventory, and perform other administrative tasks.
- **Simultaneous Usage:** Both services can be used concurrently, allowing users and administrators to interact with the system simultaneously without interference.
- **Frontend with Thymeleaf:** The frontend of the application is developed using Thymeleaf, providing a dynamic and interactive user interface.
- **Payment Integration with PayPal:** Users can make payments securely using PayPal, ensuring a smooth and reliable payment process.

## Technologies Used

- **Spring Boot:** The backend services are built using Spring Boot, providing a robust and scalable framework for developing enterprise-level applications.
- **Thymeleaf:** Thymeleaf is used for server-side rendering of HTML templates, enabling dynamic content generation and seamless integration with Spring Boot.
- **PayPal Integration:** The application integrates with PayPal's payment gateway to facilitate secure online transactions.
- **Java:** The primary programming language used for backend development is Java, known for its versatility and performance.
- **MySQL/MongoDB:** The application utilizes MySQL/MongoDB databases for storing product information, user data, and other relevant information.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Start both services: 
   ```
   $ java -jar local-user-service.jar --server.port=8080
   $ java -jar admin-service.jar --server.port=8090
   ```
4. Access the user interface by navigating to `http://localhost:8080`.
5. Access the admin interface by navigating to `http://localhost:8090`.
6. Start exploring and using the application!

## Contributions

Contributions to the project are welcome! Whether it's fixing a bug, implementing a new feature, or improving documentation, your contributions are highly appreciated. Please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions regarding the project, feel free to contact us at [email@example.com](mailto:takeswapnil8@gmail.com).

Thank you for your interest in our Shopping Cart project! Happy shopping! 🛒🎉
