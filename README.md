# Robofriends

**Robofriends** is a fun, interactive web application built with React that generates a dynamic gallery of robot friends! Each robot is uniquely created based on the user's name, using the [RoboHash API](https://robohash.org/). The robots are quirky, colorful, and randomized, providing a fun and visually engaging experience. Users can search through their robot friends by name, and the app will instantly filter the results.

## Demo

Check out the live demo [here](https://kristinakolesnyk.github.io/Robofriends/) to meet your very own robot friends!

## Features

- **Dynamic Robot Creation:** Each user gets their own robot, uniquely generated based on their name, so no two robots are alike!
- **Real-Time Search:** Users can instantly filter the list of robots by typing in the search box, and the app updates the UI in real-time.
- **Sleek Design:** The app uses the Tachyons CSS framework for fast, responsive, and minimalist styling, ensuring a clean and modern UI.

## Screenshots

![Снимок экрана 2024-07-14 в 13 47 53](https://github.com/user-attachments/assets/d1352173-db69-4b25-8735-c3a81795fbbe)

## Installation

To run the project locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/KristinaKolesnyk/Robofriends.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Robofriends
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

The app will now be running on `http://localhost:3000/`.

## Technologies Used

- **React** — for building dynamic, component-based UI
- **Tachyons** — for easy-to-use, responsive CSS styling
- **RoboHash API** — to generate fun, unique robot avatars for each user
- **JSONPlaceholder** — a free online REST API used to simulate fetching user data

## Project Structure

- **`src/components/`** — Contains reusable React components like `Card`, `CardList`, and `SearchBox`.
- **`src/containers/`** — Higher-order components like `App` that handle the logic and state of the app.
- **`src/index.js`** — The entry point for the React application.

## Acknowledgements

I hope this project helps bring clarity and enjoyment to decision-making processes. Thank you for taking the time to explore Robofriends!
