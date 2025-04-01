# IEEE SB AWH Engineering College Website

## Overview
This is the official website for the IEEE Student Branch of AWH Engineering College. It showcases our activities, events, achievements, and an interactive gallery that dynamically fetches images from Google Drive.

## Features
- **Home Page:** Provides an overview of the IEEE Student Branch.
- **Chapter Page:** Details about different chapters within the branch.
- **Execom Page:** Displays the executive committee members.
- **Gallery Page:** A visually appealing gallery fetching images dynamically from Google Drive.
- **Join IEEE Page:** Provides information and links for joining IEEE.
- **Achievements Section:** Highlights major awards and recognitions.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Gallery Integration:** Google Drive API
- **Styling:** Custom CSS for a responsive and modern design

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/ieee-sb-website.git
   ```
2. Navigate to the project folder:
   ```sh
   cd ieee-sb-website
   ```
3. Open `index.html` in a browser to view the website.

## Google Drive API Setup for Gallery
To fetch images dynamically from a Google Drive folder:
1. Get your **Google Drive Folder ID**.
2. Obtain a **Google API Key**.
3. Replace the placeholder values in `script.js`:
   ```js
   const folderId = "YOUR_FOLDER_ID";
   const apiKey = "YOUR_GOOGLE_API_KEY";
   ```

## Customization
- Modify `css/styles.css` to update the design.
- Update `index.html`, `chapter.html`, `execom.html`, etc., to add more content.
- Adjust the script in `gallery.html` to change the gallery layout.

## Contribution Guidelines
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes with meaningful commit messages.
4. Open a pull request.





