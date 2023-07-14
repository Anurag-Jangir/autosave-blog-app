# Blog Application

This is a web application built using Node.js, Express.js, and MongoDB. The application allows users to create and manage blog articles.

## Features

### Markdown Support

The application provides Markdown support for creating richly formatted blog articles. Markdown is a lightweight markup language that allows you to write plain text and convert it to HTML.

The application uses the `marked` library to render Markdown content as HTML. This enables users to write articles with formatting, such as headings, lists, links, and more.

### Autosave Feature

The application includes an autosave feature that automatically saves the content of the article while the user is writing. This ensures that progress is not lost in case of accidental page refresh or browser closure.

The autosave feature utilizes the `localStorage` API to store the article content locally within the user's browser. When the user revisits the page, the previously autosaved content is retrieved and displayed in the article form.

### Additional Features

- Create new articles with a title, description, and Markdown content.
- Edit existing articles and update their content.
- View the details of an article, including its title, description, and rendered Markdown content.
- Delete articles from the application.

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Install the dependencies:

   ```npm install```

### Usage

1. Start the application:

   ```npm start```

2. Open your web browser and navigate to ```http://localhost:5000``` to access the application.

### Dependencies
- Node.js
- Express.js
- MongoDB
- mongoose
- marked
  
### Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.
