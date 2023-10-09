# Phase4-WK2-Flask Code Challenge - Super Heros
Date Created: 01 October 2023

Developer: Brian Baraza
Contact: barazabrian87@gmail.com


# Super Heroes App

The Super Heroes App is a web application that allows users to manage information about superheroes and their powers. This README file provides an overview of the app's functionality and how to use it.

## Features

The Super Heroes App provides the following features:

1. **Hero Management**
   - Implemented Hero, Power, and HeroPower models with proper relationships.
   - Validations added to the HeroPower model for the strength attribute.
   - Validations added to the Power model for the description attribute, checking for presence, length, and allowed values.

2. **API Endpoints**
   - Implemented the following API endpoints:
     - `GET /heroes`: Returns a list of superheroes in JSON format.
     - `GET /heroes/:id`: Retrieves information about a superhero by their ID, handling both existing and non-existing heroes and returning JSON data as specified.
     - `GET /powers`: Returns a list of superpowers in JSON format.
     - `GET /powers/:id`: Retrieves information about a superpower by its ID, handling both existing and non-existing powers and returning JSON data as specified.

## Getting Started

To run the Super Heroes App on your local machine, follow these steps:

1. Clone this repository to your local machine:

   download the package: python-code-challenge-superheroes.zip

2. Extract the assignment file to a folder: cd super-heroes-app

2. Navigate to the project directory:

   ```bash
   cd super-heroes-app
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Start the application:

   ```bash
   npm start
   ```

5. The app should now be running locally on `http://localhost:3000`.

## Usage

Once the application is running, you can interact with it using the following API endpoints:

- `GET /heroes`: Retrieve a list of all superheroes.
- `GET /heroes/:id`: Retrieve information about a specific superhero by providing their ID.
- `GET /powers`: Retrieve a list of all superpowers.
- `GET /powers/:id`: Retrieve information about a specific superpower by providing its ID.

## Example Requests

### Retrieve All Superheroes

```http
GET http://localhost:3000/heroes
```

### Retrieve a Specific Superhero

```http
GET http://localhost:3000/heroes/:id
```

Replace `:id` with the ID of the superhero you want to retrieve.

### Retrieve All Superpowers

```http
GET http://localhost:3000/powers
```

### Retrieve a Specific Superpower

```http
GET http://localhost:3000/powers/:id
```

Replace `:id` with the ID of the superpower you want to retrieve.


## License

This project is licensed under the MIT License.

## Contact

If you have any questions or need assistance, please contact us the developer on: barazabrian87@gmail.com

Thank you for using the Super Heroes App! We hope you find it useful and fun to use.