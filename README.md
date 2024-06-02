# 🍕 Fast React Pizza

A very simple application where users can order pizzas from a menu.

## Feature List

### Cart

- Users can add multiple pizzas to a cart before ordering.
- Users can mark their order as "priority" for an additional 20% of the cart price.

### Menu

- The pizza menu can change, so it is loaded from an external API.

### Order

- Ordering requires the user's name, phone number, and address.
- If possible, GPS location should also be provided to make delivery easier.
- Payments are made on delivery, so no payment processing is necessary in the app.
- Users can look up their order based on the ID.

### User

- No user accounts or login required.
- Users just input their names before using the app.

## Tech Stack

- Vite
- React
- Tailwind CSS
- Redux Toolkit
- React Router
- React Query

## Installation

1. **Clone the repository**:

   ```sh
   git clone https://github.com/maxpsz/simple-pizza-ordering-app.git
   cd simple-pizza-ordering-app
   ```

2. **Install dependencies**:

   ```sh
   npm install
   ```

3. **Start the development server**:
   ```sh
   npm run dev
   ```

## Credits

This project was developed following the course **The Ultimate React Course 2024: React, Next.js, Redux & More** by **Jonas Schmedtmann**.
