# Weekly Blog

This repository hosts the source files for my weekly blog during my placement at Harper Adams University. The blog documents my experiences, learning, and progress on various projects related to data analysis and artificial intelligence.

## Table of Contents
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)


## Getting Started

### Prerequisites
- **Quarto:** Ensure you have Quarto installed. You can download it from [Quarto's official website](https://quarto.org/).

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/IndustrialPlacementProgress/Weekly_Tasks
   ```
2. Navigate to the project directory:
   ```sh
   cd Weekly_Blog
   ```
3. Render the site using Quarto:
   ```sh
   quarto render
   ```

### Project Structure
The following is an overview of the key directories and files in this repository:

- **docs/**: Contains the rendered output of the site, which GitHub Pages serves. This directory includes:
  - `index.html`: The homepage of the blog.
  - `about.html`: The About page.
  - `posts/`: Contains the HTML files for individual weekly posts.
  - `site_libs/`: Includes libraries and assets used by the site, such as CSS and JavaScript files.

- **posts/**: Contains individual `.qmd` files for each week's content along with .Rhistory and .RData. Each file represents a blog entry documenting weekly activities, learnings, and reflections. Example files:
  - `week1.qmd`
  - `week2.qmd`
  - `week3.qmd`

- **img/**: Contains image assets used in the blog posts or site design.

- **_quarto.yml**: The configuration file for the Quarto project. This file specifies project settings, including the website's title, navigation structure, output directory, and more.

- **index.qmd**: The source file for the homepage of the blog, which typically includes an introduction and links to recent posts.

- **about.qmd**: The source file for the About page, providing information about the author, the purpose of the blog, and any other relevant details.

- **styles.css**: Custom CSS file for additional styling specific to the blog.

- **.gitignore**: Specifies files and directories that Git should ignore, preventing them from being included in the version control.

- **README.md**: This file. Provides an overview of the project, instructions for getting started, and other useful information.

This structure helps organise the content and resources for the blog, making it easy to manage and update. The `docs` directory is used for the deployment of the rendered site, while the `posts` and other directories contain source materials.
