# Personal Portfolio
Visit https://chethanhn29.github.io/




# Project Portfolio

This repository contains a collection of my personal projects showcasing expertise in various domains such as NLP, Computer Vision, and more.

## Table of Contents
- [Introduction](#introduction)
- [Functions](#functions)
- [Adding New Projects](#adding-new-projects)
## Introduction

Welcome to my project portfolio! Each project demonstrates my skills in various programming languages, frameworks, and tools. This README provides guidance on functions, adding new projects, and prioritizing projects within categories.

## Functions

### `generateProjectCard(project)`

- **Purpose:** Creates a visual representation (card) for a project.
- **Usage:** This function takes a `project` object as input and generates an HTML card structure representing that project. It fills in details like title, subtitle, image, libraries used, and GitHub link.

### `redirectToGithub(githubLink)`

- **Purpose:** Opens the GitHub link of a project in a new tab.
- **Usage:** This function opens a new browser tab with the GitHub repository link of the project passed as `githubLink`.

### `toggleContent(btn, projectId)`

- **Purpose:** Toggles the visibility of project content (Read More/Read Less).
- **Usage:** This function handles the expansion and contraction of the project's content (description, tags, images) when the "Read More" or "Read Less" button is clicked. It uses the `projectId` to identify the project to expand or collapse.

## Adding New Projects

To add a new project:

1. **Update the `projects` Array:**
    - Add a new object to the `projects` array with details of your new project. Include fields like `id`, `title`, `subtitle`, `libraries`, `githubLink`, `imageSrc`, `readMoreContent`, `readLessContent`, and set `expanded` initially to `false`.

2. **Adjust Sorting for Categories:**
    - In the `filterProjects(category)` function, update the sorting arrays (`categoryButtonSorts`) for each category you plan to add the new project to.

3. **Commit Changes:**
    - Save your changes and commit them to your repository.

## Project Priority

- **Display Priority:**
    - The order of projects within the `projects` array and the sorting arrays (`categoryButtonSorts`) determines the priority for displaying projects in different categories.
    - Higher priority projects should be listed at an earlier position in the arrays.

## Contributing

Contributions, bug reports, and feature requests are encouraged! Fork this repository, make changes, and create a pull request. For major changes, please open an issue first to discuss proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

