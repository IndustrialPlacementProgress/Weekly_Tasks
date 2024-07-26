# Weekly Blog

![Blog Banner](img/blog_readme_img.png)

[Link to my Online Personal Profile](https://industrialplacementprogress.github.io/Weekly_Tasks/)

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

## Project Structure
The following is an overview of the key directories and files in this repository:

- **docs/**: Contains the rendered output of the site, which GitHub Pages serves. This directory includes:
  - `index.html`: The homepage of the blog.
  - `about.html`: The About page.
  - `posts/`: Contains the HTML files for individual weekly posts.
  - `site_libs/`: Includes libraries and assets used by the site, such as CSS and JavaScript files.

- **posts/**: Contains individual `.qmd` files for each week's content. Each file represents a blog entry documenting weekly activities, learnings, and reflections. Example files:
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

## Usage

To view and interact with the content of this project, follow these steps:

### Viewing the Blog Locally

1. **Clone the Repository**:
   First, ensure you have cloned the repository to your local machine. If you haven't done so, you can clone it using the following command:

   ```sh
   git clone https://github.com/IndustrialPlacementProgress/Weekly_Tasks.git
   ```

2. **Navigate to the Project Directory**:
Change your directory to the project's root directory:
   ```sh
   cd Weekly_Tasks
   ```

3. **Install Quarto (if not already installed)**:
Ensure Quarto is installed on your system. If not, download and install it from [Quarto's official website](https://quarto.org/).

4. **Render the Site**:
Use Quarto to render the site. This will convert the .qmd files into HTML:
   ```sh
   quarto render
   ```
The rendered files will be located in the docs directory (or _site if configured differently).

5. **View the Site**:
Open the docs/index.html file in your web browser to view the site locally. You can navigate through the pages and view each week's content.

### Accessing the Blog Online
The blog is also hosted online via GitHub Pages. You can access it at the following URL: 

[Weekly Blog](https://industrialplacementprogress.github.io/Weekly_Tasks/).


### Adding New Content
To add new content, such as additional weeks or updates:

1. **Create a New Quarto Markdown File**:
    - In the posts/ directory, create a new .qmd file.
    - Follow the existing structure and format used in previous files.

2. **Render the Site**:
    - Run quarto render to process the new content and update the docs directory.
3. **Commit and Push Changes**:
    - Add, commit, and push the changes to the repository
   ```sh
   git add .
   git commit -m "Add your comment..."
   git push origin main
   ```

4. **Update GitHub Pages**:
    - Ensure the docs directory is up to date with the latest content. If using the gh-pages branch, follow the deployment steps to update the site.