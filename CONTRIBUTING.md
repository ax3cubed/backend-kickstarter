# Contributing to BackendKickstarter

We welcome contributions to BackendKickstarter and are excited to collaborate with you! Below are guidelines for reporting issues, requesting features, and contributing code.

## How to Contribute

**Reporting Issues**:
If you encounter bugs or have ideas for improvements, please report them by opening an issue in the GitHub repository.

1. Check for existing issues: Before submitting a new issue, check if the issue has already been reported or is being addressed.
2. Submit a new issue: If it’s a new bug or suggestion, open an issue with a clear and descriptive title. Be sure to include:
    - Steps to reproduce the bug (if applicable).
    - Expected vs. actual behavior.
    - Any relevant logs or error messages.

**Requesting Features**:
Feature requests are welcome! Please submit a feature request by opening an issue and prefixing the title with "[Feature Request]". In your request, include:

- A clear description of the feature.
- Use cases or problems it solves.
- Potential examples or benefits of the feature.

**Submitting Pull Requests**:
We love receiving pull requests! To contribute code to BackendKickstarter, follow the steps below:

1. Fork the repository: Click on the “Fork” button at the top of the repository page.
2. Clone your fork: Clone the forked repository to your local machine.
    
    ```bash
    git clone https://github.com/ax3cubed/BackendKickstart.git
    cd BackendKickstart
    ```
    
3. Create a branch: Always create a new branch for your contributions. Use meaningful branch names that reflect the work being done, such as `feature/add-logging` or `bugfix/fix-typo`.
    
    ```bash
    git checkout -b feature/your-feature-name
    ```
    
4. Make your changes: Implement your changes or fixes following the project’s coding style.
5. Run tests and lint: Before submitting, ensure your changes pass the linting and test suites.
    
    ```arduino
    npm run lint
    npm run test
    ```
    
6. Commit your changes: Use meaningful and descriptive commit messages.
    
    ```sql
    git commit -m "Add feature X to improve Y"
    ```
    
7. Push your changes: Push the changes to your forked repository.
    
    ```bash
    git push origin feature/your-feature-name
    ```
    
8. Open a pull request: On the original repository, click “Pull Requests,” then click “New Pull Request.” Provide a clear description of the changes.

## Code Style and Guidelines

To maintain consistency across the project, please adhere to the following guidelines:

- **TypeScript**: Ensure all TypeScript files follow best practices for typing and structure.
- **Linting**: We use Biome for linting. Please run the following command before submitting your code:
    
    ```arduino
    npm run lint
    ```
    
- **Commit Messages**: Follow the Conventional Commits specification to write clear, descriptive commit messages. Example: `fix: resolve issue with API response validation`.

## Feature Development Workflow

If you are developing a new feature, follow these steps:

1. Open an issue: Discuss the feature in an issue before beginning work.
2. Follow the coding standards: Ensure your feature matches the overall architecture and coding standards.
3. Add tests: Ensure you add unit tests or integration tests for any new functionality.
4. Document the feature: Update the README or other relevant documentation to explain the new feature.

## Code of Conduct

We have a Code of Conduct to ensure a welcoming environment for everyone. Please review it before participating.

## License

By contributing to BackendKickstarter, you agree that your contributions will be licensed under the same ISC License that covers the project.

---

Thank you for helping improve BackendKickstarter! We value your input and contributions. If you have any questions, feel free to ask in the GitHub discussions or open an issue.