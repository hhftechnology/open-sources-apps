# Contributing Guide for HHF Curated Open-Source Collection

Thank you for your interest in contributing to the HHF Curated Open-Source Collection! We appreciate your help in making this a comprehensive and valuable resource for Open-Source as well as Unraid users.  This guide will walk you through the process of contributing, whether you're adding a new app, submitting a review, or suggesting improvements.

## Getting Started

Before you start contributing, please take a moment to review the existing apps and categories in the collection. This will help you understand the format and ensure your contributions are consistent.  You can find the collection files here:

*   [`collection.md`](collection.md): This file contains the main category structure for the apps.
*   [`unraid-apps.md`](unraid-apps.md): This file lists the apps within each category, with links to their individual pages.
*   [`review.md`](review.md): This file contains the reviews for each app.

If you're unsure about anything, don't hesitate to open an [issue](https://github.com/YOUR_USERNAME/YOUR_REPO/issues) for clarification.

## Ways to Contribute

There are several ways you can contribute to the Unraid Community Apps Collection:

*   **Adding a New App:**  Introduce an app that you think would be beneficial to the Unraid community.
*   **Adding a Review:** Share your experience with an existing app by writing a review.
*   **Suggesting Improvements:**  Help us improve the collection by suggesting new categories, better descriptions, or other enhancements.
*   **Reporting Issues:**  Let us know if you find any errors, outdated information, or other problems.

## Adding a New App (Detailed Steps)

1.  **Create a New App File:** Create a new file named `app-name.md` in the root directory of the repository.  Use kebab-case for the filename (e.g., `my-awesome-app.md`).  The filename should match the app name used in `unraid-apps.md` exactly.

2.  **Use the App Template:** Use the following template for your app file:

    ```markdown
    ## App Name

    *   Description: A concise and informative description of the app (one or two sentences).  Focus on the app's core functionality and benefits.
    *   Category: The primary category the app belongs to (e.g., Media Management, Backup, Utilities).  Refer to `collection.md` for the list of existing categories.  If the app fits into multiple categories, choose the most relevant one for its primary function.
    *   Unraid: Whether the app is readily available as an Unraid app (yes/no).  If yes, specify if it's via Community Applications (CA) with `CA:yes`.
    *   Docker: The Docker image name (if applicable) (e.g., `image-name:latest`).  Include the Docker Hub repository name (e.g., `linuxserver/sonarr`).
    *   Website: Link to the app's official website (if available).
    *   Source Code: Link to the app's source code repository (e.g., GitHub, GitLab) (if available).
    *   License: The app's license (e.g., GPL-3.0, MIT, Apache-2.0).  If it's a custom license, provide a link to the license text.

    ### Reviews

    *(Leave this section empty when adding a new app.  Reviews will be added separately)*
    ```

3.  **Add to `unraid-apps.md`:** Open `unraid-apps.md` and add a link to your new app file in the appropriate category. Follow the existing format.  For example:

    ```markdown
    ### Media Management

    *   [Plex](plex.md) - Advanced media server...
    *   [My Awesome App](my-awesome-app.md) - Description of my awesome app...
    ```

4.  **Add Category to `collection.md` (If Necessary):** If the app falls under a *new* category that isn't already in `collection.md`, you'll need to add it.

    *   Open `collection.md`.
    *   Add the new category and any necessary subcategories, following the existing structure.  Make sure the category name is linked correctly using Markdown link syntax (e.g., `[New Category](#new-category)`).  All categories must have a corresponding heading in the file.
    *   Example:

    ```markdown
    - [Software](#software)
        - [New Category](#new-category)  *(Add this if the category doesn't exist)*
            - [Subcategory 1](#subcategory-1)  *(Add subcategories as needed)*
            - [Subcategory 2](#subcategory-2)
    ```

5.  **Commit and Create a Pull Request:**

    *   Commit your changes with a descriptive message (e.g., "Add My Awesome App").
    *   Create a new branch for your commit (recommended).
    *   Submit a Pull Request (PR) to the main branch of the repository.  In the PR description, briefly explain your changes.

## Adding a Review (Detailed Steps)

1.  **Locate the App File:** Find the `app-name.md` file for the app you want to review.

2.  **Add Your Review:** Add your review under the "Reviews" section. Follow this format:

    ```markdown
    ### Reviews

    *   Rating: (e.g., 4.0 out of 5)  *(Use a consistent rating scale)*
        Author: Your Name
        Date: YYYY-MM-DD
        Review Text:  Write a detailed and helpful review.  Explain what you liked or disliked about the app, and provide specific examples.  Be objective and constructive.  Mention the Unraid version you used if relevant.
    ```

3.  **Commit and Create a Pull Request:** Follow the same steps as for adding an app (commit, create a branch, submit a PR).

## Suggesting Improvements or Reporting Issues

For general suggestions or bug reports, please open a new [issue](https://github.com/YOUR_USERNAME/YOUR_REPO/issues) on the repository.  Be as detailed as possible in your description.

## Style Guide and Best Practices

*   **Be Concise:** Keep descriptions and reviews brief and to the point.
*   **Be Descriptive:** Provide enough information for users to understand the app's purpose and functionality.
*   **Be Objective:** When writing reviews, be fair and balanced. Focus on facts and your own experience.
*   **Use Proper Markdown:** Format your contributions using Markdown syntax.
*   **Keep it Organized:**  Maintain the existing structure and formatting of the files.
*   **Proofread:** Double-check your contributions for spelling and grammar errors.

## Code of Conduct

Please remember to be respectful and considerate of other contributors and maintainers.  We are committed to creating a welcoming and inclusive community.

Thank you again for your contributions!  We look forward to reviewing your Pull Requests and making the HHF Curated Open-Source Collection even better.