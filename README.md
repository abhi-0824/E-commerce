# React Shopping Cart

Shopping cart app built with React and Firebase. Currently WIP.

## Features

- Products Display.
- Products Filter.
- Infinite Scroll.
- Cart Functions.
- Basic Inventory Management.
- Auth (Email/Password & Anonymous).
- Mock Checkout Page.
- User orders & addresses.

## Installation

- Step 1: Clone Repository and Install Packages.

cd react-shopping-cart

npm install

```

- Step 2: Create firebase-config.js file inside src/firebase directory.

```

export const firebaseConfig = {
apiKey: '',
authDomain: '',
databaseURL: '',
projectId: '',
storageBucket: '',
messagingSenderId: '',
appId: '',
};

```

- Step 3: Start the development server.

```

npm run dev

```

## Setup Firebase Project

### Firestore

Create products and users collections and carts, checkoutSessions and orders ones optionally.




```
