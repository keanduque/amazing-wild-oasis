# The Amazing Wild Oasis

this app is a small boutique hotel with 8 luxurious wooden cabins App created in Vite + React,
this app has a following feature below :

👉 Users of the app are hotel employees. They need to be logged into the application to perform tasks
👉 New users can only be signed up inside the applications (to guarantee that only actual hotel employees can get accounts)
👉 Users should be able to upload an avatar, and change their name and password
👉 App needs a table view with all cabins, showing the cabin photo, name, capacity, price, and current discount
👉 Users should be able to update or delete a cabin, and to create new cabins (including uploading a photo)
👉 App needs a table view with all bookings, showing arrival and departure dates, status, and paid amount, as well as cabin and guest data
👉 The booking status can be “unconfirmed” (booked but not yet checked in), “checked in”, or “checked out”. The table should be filterable
by this important status
👉 Other booking data includes: number of guests, number of nights, guest observations, whether they booked breakfast, breakfast price
👉 Users should be able to delete, check in, or check out a booking as the guest arrives (no editing necessary for now)
👉 Bookings may not have been paid yet on guest arrival. Therefore, on check in, users need to accept payment (outside the app), and
then confirm that payment has been received (inside the app)
👉 On check in, the guest should have the ability to add breakfast for the entire stay, if they hadn’t already
👉 Guest data should contain: full name, email, national ID, nationality, and a country flag for easy identification
👉 The initial app screen should be a dashboard, to display important information for the last 7, 30, or 90 days:
👉 A list of guests checking in and out on the current day. Users should be able to perform these tasks from here
👉 Statistics on recent bookings, sales, check-ins, and occupancy rate
👉 A chart showing all daily hotel sales, showing both “total” sales and “extras” sales (only breakfast at the moment)
👉 A chart showing statistics on stay durations, as this is an important metric for the hotel
👉 Users should be able to define a few application-wide settings: breakfast price, min and max nights/booking, max guests/booking
👉 The app needs a dark mode

-   used feature-based structure for the folder inside App

Feature Category :

-   Authentication
-   bookings
-   cabins
-   check-in-out
-   dashboard
-   settings

## Other Info:

Node version : v18.16.0

In the project directory, you can run:

## Technology Decisions / 3rd party Tools

-   Routing & Remote State management: ReactRouter
-   Styling: Styled Components
-   Remote State Management: ReactQuery
-   UI State Management: Context API
-   Form Management: React Hook Form
-   Other Tools: React Icons,React Hot Toast,Recharts,date-fns and Superbase

## 3rd party installation via Terminal

```node - Styled components
npm i styled-components
```

```node - new way of react routing with data loading in version 6.4+
npm i react-router-dom@6
```

```node - React-icons
npm i react-icons
```

-   https://reactrouter.com/en/main/routers/create-browser-router

biggest library to implement map https://react-leaflet.js.org/
https://leafletjs.com/examples/quick-start/

```node
npm i react-leaflet leaflet
```

React Date Picker https://www.npmjs.com/package/react-datepicker

```node
npm i react-datepicker
```

TailwindCSS : https://tailwindcss.com/docs/installation
https://tailwindcss.com/docs/guides/vite

Redux Toolkit

```node
npm i @reduxjs/toolkit react-redux
```

---

## Backend Supabase

---

### `npm run dev`

VITE v4.5.2

➜ Local: http://localhost:5173/
➜ Network: use --host to expose
➜ press h to show help

### `npm run server` to run fake API

data/cities.json

Index:
http://localhost:8000/

Static files:
Serving ./public directory if it exists

Endpoints:
http://localhost:8000/cities

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

-   [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
-   [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
