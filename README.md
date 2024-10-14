# Cloud Book Writer Platform

## Project Overview

The **Cloud Book Writer Platform** is a front-end React-based platform where users can create, edit, and collaborate on books. The platform allows for a user-friendly interface focused on book writing, offering unlimited sections and subsections. Each section can have multiple nested subsections, providing flexibility for authors and collaborators.

### Core Features:

1. **Unlimited Sections and Subsections**:

   - The platform allows users to create books with sections and subsections, nested infinitely.
   - For instance, a section titled "Introduction" might contain subsections like "Intro to Platform," and these can further be divided into more subsections.

2. **User Authentication**:

   - The platform supports user authentication, allowing users to sign up, log in, and manage their accounts securely.
   - It utilizes **json-server-auth** to simulate authentication and authorization.

3. **Permissions & Roles**:

   - Users can have roles like **Author** and **Collaborator**.
   - Authors can create new sections and subsections, while both Authors and Collaborators can edit sections.
   - Authors can manage collaborator permissions directly through the interface.

4. **Test Cases and Performance Optimization**:
   - Once the core features are complete, the platform includes writing unit and integration tests for React components.
   - Caching mechanisms are implemented to enhance performance and response times.

### Technologies Used:

- **React**: Front-end library for building user interfaces.
- **React Router**: For navigation and routing between pages.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **TypeScript**: Strongly typed language for building maintainable code.
- **React Hook Form**: For managing form data and validation.
- **json-server-auth**: Simulates authentication and authorization for development.
- **Cypress**: End-to-end testing framework.
- **UUID**: For generating unique IDs for sections, books, and users.

---

## Getting Started

Follow the steps below to set up the project locally.

### Prerequisites

Before you start, ensure you have the following installed:

- **Node.js (16.x or higher)**: The project uses Node.js version 20 LTS.
- **npm (10.x or higher)**: The project relies on npm for managing dependencies and scripts.

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   cd cloud-book-writer-platform
   ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
  ```bash
  npm run dev
  ```

4. To run the mock server using json-server for simulating a database and authentication, run the following command:
  ```bash
  npm run dev
  ```

5. Running Cypress Tests
  ```bash
  npm run cypress
  ```
