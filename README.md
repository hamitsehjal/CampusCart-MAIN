# CampusCart

This is the `main` repository for the CampusCart project. Here, we manage project-wide documentation, track milestones, and discuss issues related to the project.

## Code Organization and Structure

Our project is organized into separate repositories for the frontend and backend components, allowing us to maintain clear separation and efficient development for each part of the application.

### Frontend Repository

Our frontend codebase is hosted in a dedicated repository. It includes the user interface (UI) components, client-side logic, and assets required for the frontend of our application.

- **Repository**: [FrontEnd - Client](https://github.com/hamitsehjal/CampusCart-FRONTEND)

### Backend Repository

The backend code and server-side logic are stored in a separate repository. This includes APIs, database interactions, and other server-related functionality.

- **Repository**: [BackEnd - Server](https://github.com/hamitsehjal/CampusCart-BACKEND)

### Architecture

Our project follows a client-server architecture, where the frontend (client) communicates with the backend (server) to deliver a seamless user experience. Here's an overview of our architecture:

- **Client (Frontend)**: The client-side of our application is responsible for presenting the user interface, handling user interactions, and making requests to the server for data and functionality.

- **Server (Backend)**: The server-side of our application manages data storage, business logic, and responds to requests from the client. It serves as the backend API that our frontend communicates with.

Our client-server architecture ensures scalability, maintainability, and separation of concerns, allowing us to develop and deploy each component independently while offering a robust and efficient user experience.

For more detailed information on the structure of each component, please refer to the respective repository READMEs in the provided links above.

### Branching Strategy

We follow a simplified branching strategy to keep our development organized:

- We have a single main branch (`main`) that serves as the primary development branch.
- For each new feature or bug fix, team members create separate `feature` branches.
- Once a feature is complete and tested, it is `merged` into the main branch.

### CI/CD Pipelines

To ensure the quality and reliability of our code, we will set up Continuous Integration (CI) and Continuous Delivery (CD) pipelines:

- **CI Pipeline**: This pipeline is triggered on every `push` or `merge` to the `main` branch. It automatically integrates and tests code changes, helping us maintain code quality and identify issues early in the development process.

- **CD Pipeline**: The CD pipeline is triggered exclusively when a `Git tag` is pushed to the main repository. This signifies a release event, and the CD pipeline automates the deployment process to a production environment, ensuring that our code is delivered reliably and consistently.

### How to implement Branching Strategy

To contribute to this project, follow these steps to create new branches and make pull requests:

1. Clone the repository to your local machine:
   ```bash
     git clone <repository-url>
   ```
2. Create a new branch for your feature or bug fix:
   ```bash
   # Create a new branch and switch to it
   git checkout -b feature/my-feature
   ```
3. Make your code changes, commits, and push your branch to the remote repository
   ```bash
   # Make code changes and commit them
   git add .
   git commit -m "Add your descriptive commit message here"

   # Push your branch to the remote repository
   git push origin feature/my-feature
   ```

4. Create a Pull Request (PR) on GitHub:
  - Go to the GitHub repository.
  - Click on the "Pull Requests" tab.
  - Click the "New Pull Request" button.
  - Choose your branch as the source and the main branch as the target.
  - Add a descriptive title and description for your PR.
  - Click "Create Pull Request"

5. Your PR will be reviewed by team members, and any necessary discussions or changes will be made before merging.


## LICENSE
This project is not open-source and does not include an open-source license.
You can use this README.md template as a starting point for your main repository's documentation. 




