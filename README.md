# Experiment: Redux Shopping Cart

## Aim
Implement Redux for state management in shopping carts.

## Objectives
1. Configure Redux store with Toolkit.
2. Create cart slice with reducers.
3. Implement cart operations (add/remove/update).
4. Connect components to Redux store.
5. Persist cart state to localStorage.

## Technologies Used
- React 18
- Redux Toolkit 2
- React Redux
- Material UI 5
- Vite
- Redux DevTools Extension

## Features
- Product listing UI built with Material UI.
- Redux Toolkit store configured with `configureStore`.
- Cart state handled with a dedicated `cartSlice`.
- Add to cart, remove from cart, update quantity, and clear cart actions.
- Automatic persistence of cart state using `localStorage`.
- Redux DevTools support enabled for debugging.

## Folder Structure
```text
src/
├── app/
│   └── store.js
├── components/
│   ├── Cart.jsx
│   └── ProductList.jsx
├── features/
│   └── cart/
│       └── cartSlice.js
├── App.jsx
└── main.jsx
```

## How to Run
```bash
npm install
npm run dev
```

## Expected Learning Outcome
This experiment demonstrates advanced state management in a shopping cart application using Redux Toolkit and persistent client-side storage.
