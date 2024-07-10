# Restaurant Order Web Application

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Screenshot](#screenshot)


## Introduction
Our Restaurant Order Web Application allows users to explore our menu, search for dishes, add their favorite dishes to the cart, place orders, check order history, and stay connected with us by adding their contact information. 

## Features

- **View Our Menu:** Explore a culinary journey through our delectable offerings, meticulously crafted to tantalize your taste buds. Explore our menu by category, whether you're looking for brunch, lunch, dinner, or happy hour delights.

- **Search Our Menu:** Type in your meal ideas and search. We always have something in store for you.

- **Add to Cart:** Select your preferred dishes and assemble your perfect meal right from the comfort of your screen.

- **Place Your Order:** With just a click, embark on a seamless ordering process that ensures your culinary desires are swiftly fulfilled by our dedicated team.

- **Order History:** Revisit fond memories of your past orders, reminisce about the delightful flavors, and plan your future gastronomic adventures.

- **Contact Information:** Stay connected with us! Share your contact details to receive the latest updates, exclusive offers, and personalized recommendations.

## Technologies Used

- **Node.js**: Backend server environment.
- **Express**: Web framework for Node.js.
- **React**: Frontend library for building user interfaces.
- **Vite**: Next-generation frontend tooling.
- **Docker**: Containerization for easy deployment.

## Setup Instructions
### Prerequisites
 Docker
### Docker Setup
1. Clone the repository:

```bash
git clone https://github.com/heyanlu/Restaurant-Order-Web-Application.git
cd Restaurant-Order-Web-Application
```

2. Build the Docker image:
```bash
docker build -t <imageName> .
```
3. Run the Docker container:
```bash
docker run -p 3000:3000 <imageName>
```
### Frontend Setup
```bash
npm run dev
```

## Usage 
Access the frontend at http://localhost:5175.
The backend server runs at http://localhost:3000.

## Screenshot
![Blank diagram (1)](https://github.com/heyanlu/Restaurant-Order-Web-Application/assets/116776352/098fe394-499c-4c01-8fdf-2062a2d4107e)

![Blank diagram](https://github.com/heyanlu/Restaurant-Order-Web-Application/assets/116776352/79697407-c090-4561-b1db-ae0f5dd0d78e)
