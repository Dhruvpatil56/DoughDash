DoughDash
DoughDash is a comprehensive solution designed to streamline pizza ordering processes, enhance customer experiences, and improve operational efficiency for pizza delivery businesses. This repository contains the frontend implementation of DoughDash, using modern web technologies and containerization for deployment.

Table of Contents
Technologies Used
Project Structure
Installation
Usage
Contributing
License
Technologies Used
Frontend
React: A JavaScript library for building user interfaces.
React Router: A library for routing in React applications.
Styled Components: A library for styling React components using tagged template literals.
Recharts: A composable charting library built on React components.
Tailwind CSS: A utility-first CSS framework for rapid UI development.
Backend
Supabase: An open-source Firebase alternative providing backend services including authentication and database functionalities.
Deployment and Containerization
Docker: A platform for developing, shipping, and running applications in containers.
Amazon Web Services (AWS):
Elastic Container Registry (ECR): A managed AWS Docker registry service.
Elastic Container Service (ECS): A fully managed container orchestration service.
AWS Fargate: A serverless compute engine for containers.
Load Balancer: For distributing incoming application traffic.
CloudFormation: For provisioning and managing AWS infrastructure.

Project Structure
java
Copy code
DoughDash/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── styles/
│   └── utils/
├── public/
├── Dockerfile
├── docker-compose.yml
├── package.json
└── README.md
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/DoughDash.git
cd DoughDash
Install dependencies:

bash
Copy code
npm install
Set up environment variables:
Create a .env file in the root directory and add your environment variables. Refer to .env.example for required variables.

Run the development server:

bash
Copy code
npm start
Usage
Running tests:

bash
Copy code
npm test
Building for production:

bash
Copy code
npm run build
Dockerizing the application:

bash
Copy code
docker-compose up --build
Contributing
Fork the repository.
Create a new branch (git checkout -b feature/your-feature-name).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/your-feature-name).
Open a pull request.

