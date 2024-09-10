
# Recipe Finder App

This app allows users to search for dynamic recipes using the Spoonacular API. Users can view recipe images, explore details about the recipe, and order ingredients via the Foodista platform. To fully use the app, users must create an account on Foodista to access detailed recipe information and ordering options.

## Features
- **Dynamic Recipe Images**: Fetch and display real-time recipe images from the Spoonacular API.
- **Recipe Details**: View recipe descriptions, ingredients, and preparation instructions.
- **Order Ingredients**: Redirect users to Foodista, where they can order the necessary ingredients.
- **Account Creation**: Users are prompted to create an account on Foodista to access the order feature and detailed recipe pages.

## Prerequisites
- Node.js (for running the app locally)
- Spoonacular API Key
- Foodista account (for testing ordering and account-related features)

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **API Integration**: Spoonacular API (for fetching recipes), Foodista (for ordering and details)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/recipe-finder-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd recipe-finder-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up the environment variable for the Spoonacular API key. Create a `.env` file and add your API key:
   ```
   SPOONACULAR_API_KEY=your_api_key_here
   ```
5. Start the application:
   ```bash
   npm start
   ```
6. Open the app in your browser:
   ```
   http://localhost:3000
   ```

## Usage

1. **Search for a Recipe**: Enter a recipe name or keyword in the search bar.
2. **View Recipe Details**: Browse through the recipes with dynamic images fetched from the Spoonacular API.
3. **Order via Foodista**: Click on the “Order on Foodista” button to be redirected to the Foodista website where you can order the ingredients and view more detailed recipe instructions.
4. **Account Creation**: To order or access more information, users will be prompted to sign up on Foodista if they do not have an account.

## Screenshots

### Home Page

"C:\Users\veer7\Pictures\Screenshots\Screenshot 2024-09-10 220600.png"

### Search R

### Recipe Details

"C:\Users\veer7\Pictures\Screenshots\Screenshot 2024-09-10 220739.png"

## API Integration

### Spoonacular API
The Spoonacular API is used to fetch dynamic recipe information, including images, ingredients, and instructions. You must sign up for a Spoonacular API key to make requests.

### Foodista
Foodista is used for ordering ingredients and viewing detailed recipe information. Users must create an account on the Foodista platform to fully utilize these features.

## Future Improvements
- Add a favorites feature for users to save their favorite recipes.
- Implement recipe filters based on dietary preferences.
- Improve user account management, allowing in-app login to Foodista.

## License
This project is licensed under the MIT License.
