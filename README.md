"# SBA20-React"

** #Library Book Application#**
This library book application is built using React and React Router for front-end routing. It allows users to view a list of books with details such as cover images, titles, authors, edition counts, and first publish years.

**Technologies Used**
React: A JavaScript library for building user interfaces.
React Router: A routing library for React applications.
HTML/CSS: Used for styling and structuring the user interface.
JavaScript: The primary language for interactivity and logic.

**Approach**
The application is structured using multiple React components to manage the UI and data flow efficiently. It also leverages React hooks such as **useState**, **useEffect**, and **useReducer** for managing state and side effects. Here's an overview of each component used in the application:

SearchBar: Allows users to search for books by title, author, or other criteria. It provides dynamic filtering of the book list based on user input.

**BookList**: Displays a list of books fetched from a data source. It utilizes the Book component to render individual book items.

Book: Represents an individual book item with details like cover image, title, author, edition count, and first publish year. This component is reused in both the BookList and BookDetail components.

**BookDetail**: Displays detailed information about a specific book, including a larger view of the cover image and additional metadata. It may be linked from the BookList component when a user clicks on a book.

**Header**: Provides a top-level header for the application, typically containing branding and navigation links.

**Loader**: Displays a loading indicator while data is being fetched or processed, enhancing the user experience during asynchronous operations.

**Navbar**: Provides navigation links to different sections of the application, such as the home page, search page, and possibly user account pages.

Additional utility functions, error boundaries, and styling components may also be used throughout the application to improve functionality and aesthetics.

Live Site

<!-- You can view the live site here. -->

Usage Instructions
To run the application locally:

Clone this repository to your local machine.
Navigate to the project directory in your terminal.
Install dependencies using npm install.
Start the development server using npm start.
Open your browser and visit http://localhost:3000 to view the application.
Make sure you have Node.js and npm installed on your machine before running the above commands.
