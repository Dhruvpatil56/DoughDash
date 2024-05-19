
# DoughDash

DoughDash is a comprehensive solution designed to streamline pizza ordering processes, enhance customer experiences, and improve operational efficiency for pizza delivery businesses. This repository contains the frontend implementation of DoughDash, using modern web technologies and containerization for deployment.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

### Frontend
- **React**: A JavaScript library for building user interfaces.
- **React Router**: A library for routing in React applications.
- **Styled Components**: A library for styling React components using tagged template literals.
- **Recharts**: A composable charting library built on React components.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.

### Backend
- **Supabase**: An open-source Firebase alternative providing backend services including authentication and database functionalities.

### Deployment and Containerization
- **Docker**: A platform for developing, shipping, and running applications in containers.
- **Amazon Web Services (AWS)**:
  - **Elastic Container Registry (ECR)**: A managed AWS Docker registry service.
  - **Elastic Container Service (ECS)**: A fully managed container orchestration service.
  - **AWS Fargate**: A serverless compute engine for containers.
  - **Load Balancer**: For distributing incoming application traffic.
  - **CloudFormation**: For provisioning and managing AWS infrastructure.


## Project Structure
```
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
```

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/DoughDash.git
    cd DoughDash
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add your environment variables. Refer to `.env.example` for required variables.

4. **Run the development server:**
    ```bash
    npm start
    ```

## Usage

1. **Running tests:**
    ```bash
    npm test
    ```

2. **Building for production:**
    ```bash
    npm run build
    ```

3. **Dockerizing the application:**
    ```bash
    docker-compose up --build
    ```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

This README includes all the necessary information about the technologies and frameworks used in the DoughDash project, as extracted from the provided document.
