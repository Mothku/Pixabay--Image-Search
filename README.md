# Pixabay--Image-Search
Pixabay Image Search web application using JavaScript and an API key. The application allows users to search for images related to a specific query and displays the search results in a visually appealing manner.
Here's a brief description of the key components and functionalities of the code:

HTML Structure: The HTML file defines the basic structure of the web page, including the search input field, search button, and a container to display the search results.

CSS Styling: The CSS styles are applied to provide a clean and user-friendly interface. The page layout is organized using flexbox, ensuring that the content is centered and responsive. The images displayed in the search results are arranged in a grid and styled with a box-shadow effect on hover for visual feedback.

JavaScript Code: The JavaScript code handles the main functionality of the web application. It uses the Pixabay API to fetch images based on the user's search query.

Pixabay API Key: The code includes the Pixabay API key, which is required for making requests to the Pixabay API. The API key allows the application to access the Pixabay database and retrieve images based on the user's search query.

Search Functionality: When the user enters a search query and clicks the "Search" button or presses the Enter key, the searchImages function is triggered. This function takes the user's input, constructs the API URL with the appropriate search parameters (query, image type, and image size), and makes a fetch request to the Pixabay API.

Displaying Search Results: Once the API responds with the search results, the JavaScript code parses the data and dynamically creates image elements for each result. The images are displayed in the "demo1" container on the web page. When the user clicks on an image, a new tab is opened, redirecting them to the Pixabay website for more details about the image.
