# Movie Catalog Application

## About the Project

This project is a part of a movie catalog application that involves multiple components to manage movie information, ratings, and user reviews. The following Java classes are used in this project:

### CatalogItem.java
This class represents an item in the movie catalog, containing details such as movie name, description, and rating.

### Rating.java
This class represents the rating given to a movie by a user. It includes the movie ID and the rating value.

### UserRating.java
This class aggregates the ratings given by a user. It contains a list of `Rating` objects, each representing a movie rating.

### Movie.java
This class models the movie entity with attributes like movie ID and name. It includes getter and setter methods for these attributes, along with a `toString` method for easy representation.

## Key Features
- **Movie Information Management**: Handles the storage and retrieval of movie details.
- **User Ratings**: Captures and stores user ratings for various movies.
- **Catalog Display**: Aggregates and displays information about movies, including their ratings.

This project is designed to be a part of a microservices architecture, where each service (e.g., movie information service, rating service, etc.) can be developed, deployed, and scaled independently.

## How to Run

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/movie-catalog-application.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd movie-catalog-application
    ```
3. **Build the project**:
    ```sh
    mvn clean install
    ```
4. **Run the application**:
    ```sh
    mvn spring-boot:run
    ```

## Dependencies

- Spring Boot
- Maven
- Java

## Contact
For any inquiries, please contact [your-email@example.com].
