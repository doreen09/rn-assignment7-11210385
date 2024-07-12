# Open Fashion App

Open Fashion App is a user-friendly React Native application designed to provide a smooth e-commerce experience. With Open Fashion App, you can browse through products, view detailed information, and manage your shopping cart effortlessly. The app fetches product data from an external API and uses local storage to keep your cart items saved.
s
## Features
**HomeScreen**: Browse a list of products fetched from an external API.
**ProductDetailScreen**: Get detailed information about a selected product.
**CartScreen**: Manage your shopping cart, view items, and remove them as needed.
**Drawer Navigation**: Easily navigate between Home, Product Detail, and Cart screens using a swipe gesture or button.
**Add to Cart**: Add products to your cart with a simple button tap.
**Remove from Cart**: Remove items from your cart with ease.
**Local Storage**: Keep your selected items saved locally on your device using AsyncStorage.
**Data Fetching**: Enjoy seamless data retrieval from an external API using Axios.
**Asynchronous Operations**: Experience smooth data fetching and storage operations with async/await.


## Installation

1. **Clone the repository**:   ```   git clone https://github.com/doreen09/rn-assignment7-11210385.git   ```
2. **Install dependencies**:   ```   cd rn-assignment7-11210385/OpenFashion   npm install   ```
3. **Start the development server**:   ```   expo start   ```
4. **Run the app on your device or emulator**:   - For iOS, press `i` to launch the iOS simulator.   - For Android, press `a` to launch the Android emulator or scan the QR code with the Expo Go app on your Android device.

## Usage

1. **Run the app on an Android or iOS device**:
   - Use the Expo Go app to scan the QR code displayed in your terminal.

2. **Explore the app**:
   - Browse products on the Home screen.
   - Navigate to the Checkout screen to view the selected products and their total cost.
     


## Screens Overview

### HomeScreen

Displays a list of products fetched from the API. Each product has an "Add to Cart" button.

![Home](OpenFashion/assets/screenshot%201.png)

### ProductDetailScreen

Shows detailed information about a selected product, including an "Add to Cart" button.

![Checkout](OpenFashion/assets/screenshot%202.png)

### Side Menu Options

Shows other options to navigate through the app

![Side Menu](OpenFashion/assets/screenshot%203.png)


### Products

Displays items to be added to the cart with an option to remove each item.

![Products](OpenFashion/assets/screenshot%204.png)

## Usage

- **View Products**: Launch the app to see a list of available products on the HomeScreen.
- **View Product Details**: Tap on a product to view its detailed information on the ProductDetailScreen.
- **Add to Cart**: Press the "Add to Cart" button on either the HomeScreen or ProductDetailScreen to add a product to the cart.
- **View Cart**: Navigate to the CartScreen using the drawer to see all added items and remove any if needed.

## External Libraries

- **React Navigation**: For navigation and drawer components.
- **Axios**: For fetching data from the external API.
- **AsyncStorage**: For storing cart items locally.
- **React Native Reanimated**: For enhanced animations.

## Author
**Name:** Doreen Owireduaa Amankwah
**ID:** 11210385
