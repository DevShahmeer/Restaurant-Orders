
# Restaurant Order Management System

This is a simple TypeScript application that helps manage restaurant orders based on price brackets. It allows you to filter and display orders from different restaurants based on their price ranges.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js and npm installed on your machine.

## Installation

To install and run this application, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/DevShahmeer/Restaurant-Orders.git
   ```

2. Navigate to the project directory:
   ```sh
   cd restaurant-orders
   ```

3. Install the dependencies:
   ```sh
   npm install
   ```

4. Compile the TypeScript code:
   ```sh
   npm run build
   ```

## Usage

After installing and building the application, you can run it with the following command:

```sh
npm start
```

This will execute the main logic of the application, which currently filters and prints orders for restaurants within a specified price bracket (in this case, `PriceBracket.Low`).

## Functions

### `getMaxPrice(price: PriceBracket): number`

This function takes a `PriceBracket` enum as an argument and returns the maximum price allowed for that bracket.

### `getOrders(price: PriceBracket, orders: Order[][]): Order[][]`

This function filters orders based on the specified price bracket and returns a nested array of eligible orders for each restaurant.

### `printOrders(restaurants: Restaurant[], filteredOrders: Order[][]): void`

This function prints the eligible orders for each restaurant along with their names and prices.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear and concise messages.
4. Push your changes to your fork.
5. Create a pull request to the main repository.
