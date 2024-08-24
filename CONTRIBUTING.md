# Contributing

Thank you for being interested in contributing to the [Awesome Arabic Speakers](https://awesome-arabic-speakers.dev/) project! We appreciate your efforts and contributions.

## Criteria

Awesome Arabic Speakers is an awesome list. `Awesome` lists are curations of the best, **not everything**.

So, we define the criteria for contributions per category as follows (we probably will change it a bit over time):

- [Project](https://awesome-arabic-speakers.dev/categories/project/) (like organization or community): It should be established for at least a year and has a clear impact.
- [Software](https://awesome-arabic-speakers.dev/categories/software/) (like code): It should have between 100 and 200 stars on GitHub (or equivalent on other platforms).
- [Event](https://awesome-arabic-speakers.dev/categories/event/) (like conference): It should be conducted at least 2 times if it's yearly, 4 times if it's quarterly, and 8 times if it's monthly.
- [Multimedia](https://awesome-arabic-speakers.dev/categories/multimedia/) (like podcast, vodcast. or video tutorials): It should have around 10K subscribers.
- [Text](https://awesome-arabic-speakers.dev/categories/text/) (like blog): It should be live for over a year and has at least 12 posts.

Some exceptions may be allowed, but only in the narrowest limits.

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

We welcome contributions from everyone. The list covers many [categories](https://awesome-arabic-speakers.dev/categories/) like `blog`, `code`, `event`, `multimedia`, and `project`. For more details, check the [criteria for each section](#criteria).

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
The project content is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
