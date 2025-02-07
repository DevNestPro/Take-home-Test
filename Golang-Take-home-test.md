# Go Developer Take Home Test

## Objective
To create a RESTful API that provides the current PSI (Pollutant Standards Index) data, similar to the Data Gov SG API.  

This test will evaluate your skills in Test-Driven Development (TDD), REST API creation, coding structure, and database design.

## Requirements

### Project Setup
- Use Go (Golang) for development.
- Use a version control system (preferably Git) and provide a repository link.

### API Endpoints
- `GET /psi`: Retrieves the current PSI index data.
- `POST /psi`: Adds new PSI data.

### Data Model
Design a data model to store PSI data. Each record should include:
- **Timestamp**
- **PSI reading**
- **Location (optional)**

### Database
- Use **SQLite** for simplicity.
- Design and implement the necessary tables to store PSI data.

### Testing
- Use **Test-Driven Development (TDD)** practices.
- Provide **unit tests** for the API endpoints and any other significant functionality.

### Documentation
- Provide clear instructions on how to set up and run the project.
- Document the API endpoints and their usage.

## Bonus
- Implement **data validation** for PSI readings.
- Handle errors gracefully and provide meaningful error messages in the API responses.
- Implement **logging** for API requests and errors.
- Use **Docker** to containerize the application.

## Evaluation Criteria
- Code quality and structure
- Adherence to TDD practices
- REST API design and implementation
- Database design and implementation
- Documentation clarity and completeness

## Submission
- Create a **private GitHub repository**.
- Add **Calvin Cheng** (`calvinchengx`) and **Subhransu Behera** (`subhransu`) as collaborators so they can review your code.
