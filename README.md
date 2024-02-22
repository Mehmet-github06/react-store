# Store App 🛒

<div align="center">
  <img src="./src/assets/Animation.gif" />
</div>

## About the Project

In the project I created with React, after entering the login information, you are directed to a site consisting of home, products, and about pages. On this site, you can explore many products and view additional images of the desired product. The about section contains information about our team, along with links to their GitHub and LinkedIn profiles for further interaction.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Project Skeleton](#project-skeleton)
- [Screenshots](#screenshots)

## Live Demo

[Store](https://react-store-h72u.vercel.app/)

## Features

- Logging in with email and password information
- Pagination for smooth transitions between pages.
- Easy product search using the filtering feature.

## Technologies Used

- React
- Axios for API requests
- React-Router-Dom
- [DummyJSON API](https://dummyjson.com/) for products data
- Icons from [React Icons](https://react-icons.github.io/react-icons/)
- Styling with [Tailwind](https://tailwindcss.com/) and CSS 
- [Sweetalert2](https://sweetalert2.github.io/) for alert 

## Usage

- When you hover over the email and password fields in the login section, the login email address and password are visible.
- Access detailed information and reviews for each item.
- Use the search function to find specific products.

## Project Skeleton

```
Furkan Store (folder)
|
|----readme.md         
SOLUTION
├── public
│    └── index.html
├── src
│    ├── assets
│    │     └── [images]
│    ├── components
│    │     ├── Loading.jsx
│    │     ├── Navbar.jsx
│    │     ├── ProductCard.jsx    
│    │     ├── SearchInput.jsx    
│    │     ├── Stats.jsx    
│    │     └── Testimonial.jsx  
│    ├── context
│    │     ├── AuthProvider.js
│    │     └── ProductProvider.js 
│    ├── helpers
│    │     ├── data.js
│    │     └── icons.js
│    ├── pages
│    │     ├── About.jsx
│    │     ├── Home.jsx
│    │     ├── Login.jsx
│    │     ├── NotFound.jsx
│    │     ├── ProductDetail.jsx    
│    │     └── Products.jsx 
│    ├── router
│    │     ├── AppRouter.jsx
│    │     └── PrivateRouter.jsx
│    ├── App.js
│    ├── index.css
│    └── index.js
├── package.json
└── yarn.lock
```

## Screenshots

<div align="center">
  <img src="./src/assets/Screenshot_1.jpg"  width="35%" height="500" />
  <img src="./src/assets/Screenshot_2.jpg"  width="55%" height="600" />
  <img src="./src/assets/Screenshot_3.jpg"  width="90.5%" height="450" />
</div>

## Compatibility

The project is compatible with both wide-screen computers and mobile devices.

## Acknowledgments

Products data provided by [DummyJSON](https://dummyjson.com/)