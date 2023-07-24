# Wiki

This repository contains the source code for a wiki-like web application. The application allows users to create, manage, and view articles and books. It also includes a mindmap feature for visualizing and organizing information.

## Structure

The repository is organized as follows:

- `assets`: Contains various assets used by the application, including JavaScript files, CSS stylesheets, and images.
- `config`: Contains the configuration files for the application.
- `controllers`: Contains the controller files for handling requests and responses.
- `helpers`: Contains helper functions used throughout the application.
- `language`: Contains language files for internationalization.
- `migrations`: Contains database migration files.
- `models`: Contains the model files for interacting with the database.
- `views`: Contains the view files for rendering the user interface.

## Key Files

- `wiki.php`: The main entry point for the application.
- `controllers/Articles.php`, `controllers/Books.php`, `controllers/Wiki.php`: Controller files for handling article, book, and general wiki requests.
- `models/Wikiarticles_model.php`, `models/Wikibooks_model.php`: Model files for interacting with the articles and books in the database.
- `views/article.php`, `views/book.php`, `views/mindmap.php`: View files for rendering the article, book, and mindmap pages.

## Installation

1. Clone the repository.
2. Run `install.php` to set up the application.
3. Configure your web server to serve the application.

## Usage

Navigate to the application in your web browser. From there, you can create, view, and manage articles and books. You can also use the mindmap feature to visualize and organize information.
