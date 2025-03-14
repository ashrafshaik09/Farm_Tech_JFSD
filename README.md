# 🌱 **Farm Tech with Spring Boot** 

Welcome to **Farm Tech**, an online e-commerce platform that brings you closer to the farm! This project is developed as part of an academic course by a team of three Computer Science majors. The project aims to implement a **Community Supported Agriculture (CSA)** model, which connects farmers directly to consumers, eliminating intermediaries and promoting sustainable agriculture. The concept is simple: **From Farm to Plate**.

---

## **About the Project**

Farm Tech is a dynamic and feature-rich platform built using **Spring Boot**, offering a seamless and efficient user experience. It provides a marketplace where farmers can sell their produce directly to buyers, and admins can manage users, products, and orders. The project incorporates **Roles Based Access Control (RBAC)** for three key user types:

- **Admin**: Manages users, products, and orders on the platform.
- **User (Buyer)**: Browses, adds items to the cart, and makes purchases.
- **Farmer**: Lists products, manages inventory, and fulfills orders.

---

##  **Technologies Used**

- **Spring Boot**: The backbone of the application for building the RESTful API.
- **Spring MVC**: For web application development.
- **JPA/Hibernate**: Used for data persistence.
- **MySQL**: Database to store user, product, and order data.
- **Thymeleaf**: For rendering dynamic HTML views.
- **Maven**: Build tool used to manage dependencies and build the project.
- **Roles-Based Access Control (RBAC)**: Secures the system by ensuring users can access features based on their roles.

---

##  **Key Features**

- **Role-based Access**: Admin, Farmer, and Buyer roles ensure a secure and customizable experience.
- **Product Management**: Farmers can list their produce, update it, and manage stock.
- **Order Management**: Buyers can place orders, view their cart, and proceed with checkout. Admins can track and manage orders.
- **Buyer Profile**: Buyers can register, view their profiles, and manage their purchases.
- **Farmer Profile**: Farmers can manage their personal details, products, and orders.
- **Location Management**: Locations for farmers are managed and displayed.
- **Admin Dashboard**: Admins can view, add, and delete users, products, and more.

---

##  **Getting Started**

### Prerequisites
To run this project locally, ensure that you have the following installed:

- **Java 17 or later** (JDK)
- **Maven** (for managing dependencies and building the project)
- **MySQL** (or another database with JDBC support)

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ashrafshaik09/farm_tech_jfsd.git
    cd farm_tech_jfsd
    ```

2. **Configure your database**:  
   Create a `farmtech` database in MySQL and update the `application.properties` file found in `src/main/resources/` with your database credentials.

    Example:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/farmtech
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update
    ```

3. **Build the project**:
    Use Maven to build the project:
    ```bash
    mvn clean install
    ```

4. **Run the application**:
    Once the build is successful, you can run the project with:
    ```bash
    mvn spring-boot:run
    ```

    The application should now be accessible at: `http://localhost:8080`.

---


## **Contributing**

We welcome contributions to improve **Farm Tech**! If you'd like to help, you can:

- Fork the repository
- Create a feature branch (`git checkout -b feature-branch`)
- Commit your changes (`git commit -am 'Add new feature'`)
- Push to the branch (`git push origin feature-branch`)
- Open a Pull Request

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

##  **Acknowledgements**

- **Spring Boot** for providing a comprehensive framework for building web applications.
- **Our professors and peers** for feedback and support throughout the development process.

---

Thank you for checking out **Farm Tech**! We're excited to have you experience the benefits of **CSA** and look forward to your feedback!

---
