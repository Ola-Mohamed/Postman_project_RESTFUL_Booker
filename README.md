

# RESTful Booker API Testing Project

This project is focused on testing the RESTful Booker API using **Postman**. It covers various API testing techniques to verify the functionality of key endpoints and ensure the robustness of the system. The testing suite includes comprehensive test cases for booking creation, retrieval, updates, and deletion.

## Project Overview

The **RESTful Booker** API is a web service used for booking scenarios, and this project utilizes Postman to automate and validate various endpoints. The tests are designed to verify that the API works as expected, following best practices for both functional and automated testing.

## Key Features

- **Automated Test Cases**: Tests for CRUD (Create, Read, Update, Delete) operations.
- **Postman Collection & Environment**: Pre-configured for easy use and scalability.
- **Data-Driven Testing**: Implemented tests using different sets of data.
- **Dynamic Variables**: Utilized Postman’s scripting capabilities to handle dynamic variables like booking IDs.
- **Assertions**: Verified the status codes, response bodies, and headers using Postman assertions.

## API Scenarios Tested

- **Create Booking**: Tested POST requests to create new bookings with varying data inputs.
- **Get Booking**: Validated GET requests to retrieve booking details.
- **Update Booking**: Tested PUT and PATCH requests for updating booking information.
- **Delete Booking**: Ensured DELETE requests properly remove booking data.
- **Authorization**: Tested requests requiring authentication with a valid token.
  
## Tools Used

- **Postman**: For creating, running, and automating API tests.
- **JSON**: For sending and receiving data in API requests.
(optional).

## How to Run the Tests

1. Clone the repository:
   ```bash
   git clone https://github.com/Ola-Mohamed/Postman_project_RESTFUL_Booker.git
   ```

2. Import the Postman collection and environment from the `/Postman` folder into your Postman application.

3. Run the collection manually in Postman or via **Newman** for automation:
   ```bash
   newman run Restful_Booker_Collection.json -e Restful_Booker_Environment.json
   ```

## Next Steps

- Integrate this testing suite with a CI/CD pipeline for automated test execution.
- Expand test cases to cover edge cases and additional scenarios.
  
## Contributions

Feel free to contribute to this project by creating pull requests, submitting issues, or suggesting enhancements.

---
