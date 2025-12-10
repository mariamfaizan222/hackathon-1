# Quickstart: Contributing to the Docusaurus Book

This guide provides the essential steps to get started with contributing new content to the book.

## Prerequisites

-   Node.js (LTS version)
-   npm or yarn
-   Git

## 1. Set up the Project

1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

## 2. Run the Development Server

Start the Docusaurus development server to see a live preview of the site.

```bash
npm start
```

Open your browser and navigate to `http://localhost:3000`. You should see the book's home page.

## 3. Create New Content

1.  **Create a new branch**:
    ```bash
    git checkout -b feature/my-new-lesson
    ```

2.  **Add a new lesson**:
    -   Navigate to the `docs` directory.
    -   Find the appropriate chapter directory (e.g., `docs/01-introduction`).
    -   Create a new markdown file with a numbered prefix (e.g., `04-my-new-lesson.md`).

3.  **Write your content**:
    -   Open the new markdown file and add your content. Start with a top-level heading (`#`) for the title.

4.  **View your changes**:
    -   The development server will automatically reload, and you should see your new lesson in the sidebar.

## 4. Submit Your Contribution

1.  **Commit your changes**:
    ```bash
    git add .
    git commit -m "feat: add my-new-lesson"
    ```

2.  **Push your branch**:
    ```bash
    git push -u origin feature/my-new-lesson
    ```

3.  **Create a pull request**:
    -   Go to the repository on GitHub and create a new pull request from your branch.
    -   Fill out the pull request template and request a review.
