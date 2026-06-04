# Image Search Engine

## Overview
The **Image Search Engine** is a web-based application that allows users to search for high-quality images instantly using the Unsplash API. Users can enter keywords, view related images in a responsive grid layout, and load additional results with the Show More feature.

## Features
### Image Search
- Search images using keywords
- Fetches real-time image results from the **Unsplash API**
- Displays high-quality images dynamically

### Show More Functionality
- Load additional images without refreshing the page
- Supports pagination for continuous browsing
- Enhances user experience with seamless image loading

### Image Preview
- Click on any image to open it on Unsplash
- View image details directly on the Unsplash website
- Opens in a new browser tab

### User Interface
- Clean and modern design
- Responsive image grid layout
- Easy-to-use search functionality
- Attractive color scheme and styling

## Technologies Used
- **HTML5** → Structure of the application
- **CSS3** → Styling, layout, and responsive design
- **JavaScript** → API integration and dynamic content handling
- **Unsplash API** → Fetching and displaying images

## Project Structure
```
Image-Search-Engine/
│
├── index.html      # Main structure of the application
├── style.css       # Styling and responsive layout
├── script.js       # Image search logic and API integration
└── images/         # Project assets and favicon
```

## Software Requirements
- Any modern web browser (Chrome, Edge, Firefox, etc.)
- Code editor (VS Code recommended)
- Internet connection (required for API requests)

## How It Works
1. Enter a keyword in the search box.
2. Click the **Search** button.
3. The application sends a request to the Unsplash API.
4. Relevant images are fetched and displayed in a grid layout.
5. Click **Show More** to load additional images.
6. Click any image to view it on Unsplash in a new tab.

## How to Run the Project
1. Download or clone the repository:
   ```bash
   git clone https://github.com/your-username/image-search-engine.git
   ```
2. Open the project folder in VS Code.
3. Add your Unsplash API Access Key in `script.js`:
   ```javascript
   const accessKey = "YOUR_ACCESS_KEY";
   ```
4. Open **index.html** in any modern web browser.
5. Search for any image and explore the results.