## Medical Records Analyzer

This C# program analyzes medical records data retrieved from an API endpoint and calculates the average body temperature for a given user. The program fetches medical records for a specific user ID from the provided API, extracts the body temperature readings from the records, calculates the average temperature, and returns the result.

### Features:
- Utilizes the HttpClient class to make HTTP requests to the API endpoint.
- Parses the JSON response using Newtonsoft.Json.Linq library.
- Handles pagination to retrieve all available records for the specified user.
- Calculates the average body temperature from the fetched data.

### Usage:
1. Run the program.
2. Enter the user ID for which you want to calculate the average body temperature.
3. The program will fetch the medical records, calculate the average temperature, and display the result.

### Dependencies:
- Newtonsoft.Json v12.0.3

### Notes:
- This program assumes that the API response contains medical records data in the specified format. Any changes to the API response structure may require adjustments to the code.
- Pagination handling is implemented to retrieve all available records. However, there may be performance implications for large datasets.
