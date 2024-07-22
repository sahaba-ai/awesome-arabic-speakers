# Contributing to Awesome Arabic Speakers

Thank you for your interest in contributing to the Awesome Arabic Speakers project! We appreciate your efforts and contributions.

## Running the Project Locally

To run this project locally, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:

- [Hugo (extended edition, v0.112.0 or later)](https://gohugo.io/getting-started/installing/)
- [Git](https://git-scm.com/)

### Steps

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/sahaba-ai/awesome-arabic-speakers.git
    cd awesome-arabic-speakers
    ```

2. **Install Dependencies**:
    ```sh
    hugo mod get
    ```

3. **Run the Hugo Server**:
    ```sh
    hugo server
    ```

4. **Open Your Browser**:
    - Open your browser and go to `http://localhost:1313` to see the site running locally.

5. **Reflect Changes Locally**:
    - To build the project locally and see the changes, you need to run the Hugo server with the draft content enabled:
    ```sh
    hugo server -D
    ```

### Notes for Windows Users

- Do not use the Command Prompt or Windows PowerShell.
- Use PowerShell or a Linux terminal such as WSL or Git Bash.

## How to Contribute

We welcome contributions from everyone. The list covers many categories like `blog`, `code`, `event`, `people`, `podcast`, and `project`. The criteria of each category will be defined later.

### Steps to Contribute

1. **Fork the Repository**:
    - Click the "Fork" button at the top-right corner of this page to create a copy of this repository under your GitHub account.

2. **Clone Your Fork**:
    ```sh
    git clone https://github.com/<your-username>/awesome-arabic-speakers.git
    cd awesome-arabic-speakers
    ```

3. **Create a New Branch**:
    ```sh
    git checkout -b feature/your-feature-name
    ```

4. **Make Your Changes**:
    - Add your contributions (e.g., new categories, links, or improvements).

5. **Commit Your Changes**:
    ```sh
    git add .
    git commit -m "feat: add new feature"
    ```

6. **Push to Your Fork**:
    ```sh
    git push origin feature/your-feature-name
    ```

7. **Create a Pull Request**:
    - Go to the original repository on GitHub and create a new pull request from your fork.

### Contribution Guidelines

- Follow the existing code style and structure.
- Ensure that your contributions are well-documented.
- Test your changes to make sure they work as expected.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We appreciate all contributions from the community. Your efforts help make this project better and more valuable to everyone.
