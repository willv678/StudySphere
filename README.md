# Study Sphere

## Project Description
A full-stack, real-time collaboration platform designed to help University of Georgia students connect and collaborate on academic work. The application serves as a central hub for students to create and join study rooms for specific courses, share resources, and communicate in real-time, streamlining the academic experience.

## Key Features
- **User Authentication:** Secure user registration, login, and profile management.
- **Real-time Collaboration:** Live chat within study rooms powered by WebSockets.
- **Course & Room Management:** Users can create and join study rooms tied to specific UGA courses.
- **Resource Sharing:** Functionality to share and access study materials within each room.

---

## Tech Stack
- **Frontend:**
  - **React:** A JavaScript library for building the user interface.
  - **Tailwind CSS:** A utility-first CSS framework for rapid styling.
- **Backend:**
  - **Python:** The core programming language.
  - **Django:** A high-level Python web framework.
  - **Django Channels:** Enables real-time functionality with WebSockets.
- **Database:**
  - **PostgreSQL:** A powerful, open-source relational database.
- **DevOps:**
  - **Docker:** For containerizing the application for consistent development and deployment environments.
  - **Cloud Deployment:** Application is designed for deployment on a cloud provider like AWS or GCP.

---

## Getting Started

### Prerequisites
- [Docker](https://www.docker.com/get-started)
- [Node.js](https://nodejs.org/en/download/)
- [Python 3.x](https://www.python.org/downloads/)

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/uga-study-sphere.git](https://github.com/your-username/uga-study-sphere.git)
    cd uga-study-sphere
    ```
2.  **Set up environment variables:**
    Create a `.env` file in the root directory and add the following (replace with your own values):
    ```
    SECRET_KEY=your_django_secret_key
    DEBUG=True
    DATABASE_URL=postgres://user:password@db:5432/db_name
    ```
3.  **Build and run with Docker Compose:**
    ```bash
    docker-compose up --build
    ```
    This will build the Docker images, run the containers, and set up the database. The frontend will be available at `http://localhost:3000` and the backend at `http://localhost:8000`.

---

## Contributing
We welcome contributions! Please feel free to open a pull request with any bug fixes, features, or improvements.

---

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
