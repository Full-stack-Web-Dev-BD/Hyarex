# Project Hyarex

## Overview
The project aims to develop a web application facilitating buyers to view and request quotations for products from the Chinese marketplace. The application involves admin and agents on the backend side, with distinct functionalities for each user role.

## Tech-Stack
### Frontend
- **React**: A JavaScript library for building user interfaces. React allows the creation of reusable UI components, making the development process more efficient and maintainable.

- **Next.js**: A React framework for building server-rendered applications. It provides features like server-side rendering and automatic code splitting, enhancing performance and SEO.

- **Typescript**: A superset of JavaScript that adds static typing. Typescript helps catch potential errors during development, making the codebase more robust and easier to maintain.

- **Tailwind CSS**: A utility-first CSS framework that allows for rapid styling without writing custom CSS. It promotes consistency and speeds up the styling process.

### Backend
- **Node.js**: A JavaScript runtime for server-side development. Node.js is known for its fast execution and event-driven architecture, making it suitable for building scalable network applications.

- **Express.js or Nest.js**: Express.js is a minimalistic web framework for Node.js, while Nest.js is a full-featured framework inspired by Angular. Both provide a structured approach to building APIs.

- **PostgreSQL**: A powerful open-source relational database. PostgreSQL is known for its reliability, extensibility, and support for complex queries.

### Third-Party APIs
- **Sendgrid**: A cloud-based email service for sending transactional and marketing emails.

- **Payment API (Details to be shared)**: Integration with a secure payment gateway to handle financial transactions.

- **Chinese platform APIs**: Integration with APIs from Chinese marketplaces to fetch product data and manage orders.

- **Libretranslate API**: A self-hosted translation API for multilingual support in the application.

- **Chinese web app API integration**: Integration with the Chinese web app to enhance the user experience for buyers.

## Project Structure

### Frontend Development

#### Auth Page
- **Sign-in, Sign-up via e-mail verification, Forget password**: Essential authentication features for user security.

#### Dashboard Page
- **Customized based on user role (Admin, Agents, Buyer)**: Provides a tailored view for each user type, improving user experience and efficiency.

#### User Profile
- **View, update profile; Update password**: Enables users to manage their account information easily.

#### Products Page
- **View products; Save in wishlist; View product details**: Streamlines the product browsing and selection process for buyers.

#### Warehouse Page
- **List of products in the warehouse; Filter products by buyers**: Facilitates efficient inventory management.

#### Orders Page
- **Display order information**: Allows users to track and manage their orders seamlessly.

#### Support Page
- **Allow users to send messages to Admin; Admin responds to support requests**: Enhances communication between users and admin for issue resolution.

#### E-Wallet
- **Display balance; Deposit and withdraw functionality**: Provides a convenient way for buyers to manage their funds within the platform.

#### Translation
- **Integration with Libretranslate API for translation**: Enables a multilingual user interface, enhancing accessibility for users worldwide.

### Backend Development

#### Admin Functionalities
- **Aggregated analytics**: Provides valuable insights for informed decision-making.

- **Access client accounts**: Simplifies the admin's ability to manage user accounts and resolve issues.

- **Support requests handling; Quotations management**: Streamlines communication and order processing.

- **Agent account creation**: Facilitates the onboarding of agents for extended business reach.

#### Agent Functionalities
- **Login and dashboard**: Provides agents with a centralized view of their tasks.

- **Communication with Admin**: Enables effective collaboration between agents and admin.

- **Past orders and payment history**: Allows agents to track their performance and earnings.

#### Buyer Functionalities
- **Sign-up with email verification; Subscription plans selection**: Ensures secure user registration and offers subscription options.

- **Product search with filters; Wishlist management**: Enhances the buyer's shopping experience with advanced search and product organization features.

- **Quotation requests and responses**: Streamlines the process of requesting and responding to quotations.

- **E-Wallet management**: Allows buyers to manage their funds within the platform easily.

#### E-Wallet
- **Rechargeable balance; Record keeping**: Offers a convenient and secure financial management system.

#### Integration
- **Connect with third-party APIs; Chinese platform APIs integration; Libretranslate API integration; Payment API integration**: Enhances the application's functionality by integrating external services.

### Deployment
- **Deploy frontend and backend to hosting services (e.g., AWS, Heroku)**: Ensures the application is accessible to users globally.

- **Set up continuous integration and deployment pipelines**: Automates the deployment process for efficient updates.

### Project Management
- **Use version control (e.g., Git)**: Facilitates collaboration and version tracking.

- **Implement agile methodologies (e.g., Scrum)**: Ensures an iterative and adaptive development process.

- **Collaborate using project management tools (e.g., Jira)**: Enhances team coordination and task tracking.

## Development Process
1. Define project requirements and features
2. Design database schema
3. Set up frontend project structure and components
4. Implement frontend functionality iteratively
5. Set up backend project structure and endpoints
6. Implement backend functionality iteratively
7. Integrate frontend and backend
8. Test and debug
9. Implement third-party API integrations
10. Conduct user acceptance testing
11. Deploy to staging environment
12. Address feedback and issues
13. Final deployment to production

## Future Development
- **Plan for adding new features**: Consider future enhancements to keep the application competitive.

- **Allocate income for continuous development**: Ensure resources are available for ongoing improvements.

- **Build a strong relationship with the developer**: Foster a collaborative and trust-based partnership.

## Conclusion
Project Hyarex aims to create a robust and user-friendly web application with detailed functionalities for different user roles. The provided plan covers the development process, technology stack, and future considerations for continuous improvement.
