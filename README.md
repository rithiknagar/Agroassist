<h1 align="center">AgroAssist - Modernize Farming Practices <br /></h1>  
<p align="center">
[Live Demo on Vercel](https://agrotest-pi.vercel.app/)
</p>
<p align="center">
  <img src="https://github.com/rithiknagar/Agroassist/blob/main/Screenshot%202024-11-09%20183519.png?raw=true" width="2000" >
</p>




## 🌱Agricultural Web Application  with Reactjs + Expressjs + Nodejs + MongoDB (MERN)💻

## Features

- Seller Profile
- Add/Delete Products
- Edit Profile
- Add/Edit Personal & Company Address
- Farmer Profile
- Add/Delete Grains
- Edit Profile
- Add/Edit Address
- Buy Seeds/Pesticides or Rent Machines
- Consumer
- Edit Profile
- Add/Edit Address
- Buy Materials From Farmer
- Cart Page
- Change Quantity
- Remove Product from Cart Page
and much more

## Usage

### ES Modules in Node

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```
Create a .env file inside frontend and add the following

```
REACT_APP_GOOGLE_KEY = "add google map api key"
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

## License

The MIT License

Copyright (c) Rithik nagar


