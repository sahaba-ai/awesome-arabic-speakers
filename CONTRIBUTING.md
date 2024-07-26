# Contributing

Thank you for being interested in contributing to the [Awesome Arabic Speakers](https://awesome-arabic-speakers.dev/) project! We appreciate your efforts and contributions.

## Running the Project Locally

To run this project locally, follow the next steps.

### Prerequisites

Make sure you have the following installed on your machine:

- [Hugo (extended edition, v0.112.0 or later)](https://gohugo.io/getting-started/installing/)
- [Git](https://git-scm.com/)

### Steps

1. **Clone the repository**:
    ```sh
    git clone https://github.com/sahaba-ai/awesome-arabic-speakers.git
    cd awesome-arabic-speakers
    ```

2. **Install dependencies**:
    ```sh
    hugo mod get
    ```

3. **Run the Hugo server**:
    ```sh
    hugo server
    ```

4. **Open your browser**:
    Open your browser and go to `http://localhost:1313` to see the site running locally.

1. **Reflect changes locally**:
    To build the project locally and see the changes, you need to run the Hugo server with the draft content enabled:
    ```sh
    hugo server -D
    ```

## How to Contribute

We welcome contributions from everyone. The list covers many [categories](https://awesome-arabic-speakers.dev/categories/) like `audio`, `blog`, `code`, `event`, `project`, and `video`. The criteria of each category will be defined later.

### Steps to Contribute

1. **Fork the repository**:
    Click the "Fork" button at the top-right corner of this page to create a copy of this repository under your GitHub account.

1. **Clone your fork**:
    ```sh
    git clone https://github.com/<your-username>/awesome-arabic-speakers.git
    cd awesome-arabic-speakers
    ```

2. **Create a new branch**:
    ```sh
    git checkout -b feature/your-feature-name
    ```

3. **Make your changes**:
    Add your contributions (e.g., new categories, links, or improvements).

4. **Commit your changes**:
    We use the [Keep a Changelog](https://keepachangelog.com/en/1.1.0/#how) commit message convention.
    ```sh
    git add .
    git commit -m "added: add new feature"
    ```

5. **Push to your fork**:
    ```sh
    git push origin feature/your-feature-name
    ```

6. **Create a pull request**:
   Go to the original repository on GitHub and create a new pull request from your fork.

### Contribution Guidelines

- Follow the existing code style and structure.
- Ensure that your contributions are well-documented.
- Test your changes to make sure they work as expected.

## License

The project code is licensed under the [MIT License](LICENSE).
The project content is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
