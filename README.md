```
# Recipe Sharing App

## Description

The Recipe Sharing App is a web application that allows users to create, view, and delete recipes. It is built using Spring Boot, providing a RESTful API for managing recipes.

## Features

- **Get All Recipes**: Retrieve a list of all recipes.
- **Get Recipe by ID**: Fetch details of a specific recipe by its ID.
- **Create Recipe**: Add a new recipe with its details.
- **Delete Recipe**: Remove a recipe from the database.
  
## Technologies Used

- Java 17
- Spring Boot 3.3.3
- Spring Data JPA
- H2 Database (in-memory)
- Maven

## Getting Started

### Prerequisites

- Java 17
- Maven
```
### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/recipeapp.git
   cd recipeapp
   ```

2. Build the project using Maven:

   ```bash
   mvn clean install
   ```

3. Run the application:

   ```bash
   mvn spring-boot:run
   ```

   The application will start on [http://localhost:8080](http://localhost:8080).

### API Endpoints

- **GET /api/recipes**: Retrieve all recipes.
- **GET /api/recipes/{id}**: Retrieve a recipe by ID.
- **POST /api/recipes**: Create a new recipe.  
  **Request Body:**
  ```json
  {
      "name": "Spaghetti Carbonara",
      "ingredients": "Spaghetti, eggs, pancetta, Parmesan cheese, black pepper",
      "instructions": "Boil spaghetti. Fry pancetta. Mix eggs and cheese. Combine all."
  }
  ```
- **DELETE /api/recipes/{id}**: Delete a recipe by ID.

### Testing

Run tests using:

```bash
mvn test
```

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to the Spring community for the fantastic framework.
- Inspiration from various recipe sharing platforms.

```

