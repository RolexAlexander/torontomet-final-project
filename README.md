# AnimeHub Project

AnimeHub is a simple single-page website developed with Flask to facilitate product ordering for AnimeHub's one-year anniversary. Users can browse different packages and place orders with flat-rate shipping to various regions. The backend uses MongoDB to store order information.

## Features:
- **Single Page Layout**: Clean and simple design with sections for Introduction, Package Ordering, Store & Hours, Corporate Information, and Contact.
- **Package Ordering**: Allows users to select a package and input shipping details.
- **MongoDB Integration**: Orders are saved to a MongoDB database.
- **Tailwind CSS**: Styling framework used for responsiveness and layout.

## Live Version:
- [AnimeHub Landing Page](https://rolexalexander.github.io/torontomet-final-project)

## Repository:
- [GitHub Repo](https://github.com/RolexAlexander/torontomet-final-project.git)

## Setup Instructions:
1. Rename `env.example` to `.env` and fill in the required MongoDB URI and other environment variables.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```
   python main.py
   ```

## Project Structure:
- `main.py`: Flask app backend logic
- `.env`: Environment variables for MongoDB
- `index.html`: Frontend HTML template
- `style.css`: Tailwind-styled CSS for the page
- `assets/`: Folder containing static files
  - `logo.jpg`: Logo image for the website
