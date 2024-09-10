
# Recipe Explorer App

A web application that helps users explore dynamic images of recipes fetched from the **Spoonacular API**. Users can get detailed recipe information and even place orders by visiting **Foodista**, a comprehensive platform for food enthusiasts. The app allows users to create accounts to manage their recipes and orders.

## Features

- **Dynamic Recipe Images**: Fetch and display recipe images dynamically using the Spoonacular API.
- **Recipe Information**: View detailed recipe information, including ingredients, preparation steps, and nutritional facts.
- **Foodista Integration**: Users can click on recipes to be redirected to Foodista for ordering and further details.
- **Account Creation**: Users must create accounts to manage their favorite recipes and orders.
- **User-Friendly Interface**: Simple and intuitive interface for seamless exploration.

## Demo

![Screenshot 2024-09-10 220600](https://github.com/user-attachments/assets/99bd09ac-54b7-4689-b170-7f431bedcfcb)

*The main home page displaying dynamic recipe images fetched using the Spoonacular API.*

![Screenshot 2024-09-10 220739](https://github.com/user-attachments/assets/7133d72b-2606-4dbb-881b-1ca65b120fe8)

*Recipe details page, with options to visit Foodista for more information.*

![Screenshot 2024-09-10 222554](https://github.com/user-attachments/assets/f66bb8df-3dd3-44d7-abcc-329571da354f)

*Redirect to Foodista for placing orders and getting detailed recipe instructions.*

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js
- **API**: [Spoonacular API](https://spoonacular.com/food-api)
- **Platform**: [Foodista](https://www.foodista.com)

## Prerequisites

To run the project locally, you’ll need:

- Node.js installed on your machine
- Spoonacular API key (sign up [here](https://spoonacular.com/food-api))

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/recipe-explorer-app.git
   cd recipe-explorer-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Spoonacular API key:
   ```env
   SPOONACULAR_API_KEY=your-api-key-here
   ```

4. Run the project:
   ```bash
   npm start
   ```

5. Open the app in your browser:
   ```bash
   http://localhost:3000
   ```

## Usage

1. **Browse Recipes**: Once the app is running, browse through dynamic recipe images on the home page.
2. **View Recipe Details**: Click on any recipe image to view detailed information, including ingredients and preparation steps.
3. **Place Order on Foodista**: To order a recipe or get more detailed information, click the "Order on Foodista" button, which will redirect you to the respective recipe page on Foodista.
4. **Create an Account**: Before placing an order, users must create an account to save their favorite recipes and manage their orders.

## API Reference

- **Spoonacular API**: The app fetches recipes, images, and nutritional data from the Spoonacular API.
  - **GET** `/recipes/complexSearch`
  - **GET** `/recipes/{id}/information`

## Screenshots

1. **Home Page**  
   ![Home Page](./screenshots/home-page.png)

2. **Recipe Details Page**  
   ![Recipe Details Page](./screenshots/recipe-details-page.png)

3. **Foodista Redirection**  
   ![Order on Foodista](./screenshots/foodista-order.png)

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or suggestions, feel free to reach out:
- Email: roushankumar172911@gmail.com
