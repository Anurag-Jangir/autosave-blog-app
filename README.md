# Blog Application

This is a web application built using Node.js, Express.js, and MongoDB. The application allows users to create and manage blog articles.

## Features

### Markdown Support

The application provides Markdown support for creating richly formatted blog articles. Markdown is a lightweight markup language that allows you to write plain text and convert it to HTML.

The application uses the `marked` library to render Markdown content as HTML. This enables users to write articles with formatting, such as headings, lists, links, and more.

### Autosave Feature

The application includes an autosave feature that automatically saves the content of the article while the user is writing. This ensures that progress is not lost in case of accidental page refresh or browser closure.

The autosave feature utilizes the `localStorage` API to store the article content locally within the user's browser. When the user revisits the page, the previously autosaved content is retrieved and displayed in the article form.

### Slugify for URL Generation

The application uses the `slugify` library to generate URL-friendly slugs for article titles. Slugify is a library that converts a given string into a URL slug, removing any special characters, converting spaces to hyphens, and making the text lowercase.

Benefits of using slugify for URL generation:
- Creates clean and readable URLs
- Improves SEO by including relevant keywords in the URL
- Prevents issues with special characters or spaces in the URL
- Enhances user experience by providing user-friendly and memorable URLs

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>

2. Install the dependencies:

   ```npm install```

### Usage

1. Start the application:

   ```npm run start```

2. Open your web browser and navigate to ```http://localhost:5000``` to access the application.

### Dependencies
- Node.js
- Express.js
- MongoDB
- mongoose
- marked
  
### Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.
