# Booker_project
This is a repo for the API testing of the Booker_project
**API Testing with Postman**

### Description
This project includes a series of Postman tests designed to validate the responses from a booking API. The API is expected to return JSON data, including booking IDs and tokens associated with various booking information.

### Prerequisites
To run these tests, you will need:
- [Postman](https://www.postman.com/downloads/) installed on your machine.

### Installing
1. Clone the repository to your local machine.
2. Open Postman.
3. Import the Postman collection and environment files (if available) into Postman.

### Tests Included
Here are the tests included in this Postman collection:

1. **Status Code is 200**
   - Validates that the API response status is 200 OK.

2. **Token is Alphanumeric**
   - Checks if the token received in the API response is an alphanumeric string.

3. **Booking ID Exists and is a Number**
   - Loops through all booking IDs in the response to ensure they exist and are numbers.

### Example API Response
The API is expected to return responses in the following format:
```json
[
    {
        "bookingid": 848
    },
    {
        "bookingid": 709
    },
    {
        "bookingid": 683
    }
]
```
OR for tokens:
```json
{
    "token": "12b52b28f214a93"
}
```

### Running the Tests
1. Select the imported Postman collection.
2. Choose the environment (if applicable).
3. Click on the “Run” button to execute all tests in the collection.

### Test Results
After running the tests, Postman will display the test results. Each test will be marked as passed or failed based on the response data from the API.

### Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

### Acknowledgments
* Thanks to all contributors to this project.
* Inspired by the need for robust API testing to ensure quality and reliability.

---

Adjust the above template to fit your project’s specific details, requirements, and structure. Make sure to include any additional information that will help others understand, use, and contribute to your project.
