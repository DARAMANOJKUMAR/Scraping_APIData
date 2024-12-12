Project 1: Automating API Extraction and Data Appending

Understanding the Task:
Automated data extraction from the CoinMarketCap API to fetch cryptocurrency information and append it to an existing dataset.

Steps Performed:

1.API Connection:
Imported required libraries, such as requests for API interaction and json for data parsing.
Configured API parameters (e.g., start index, limit, and currency conversion) to specify the data to fetch.
Added necessary headers, including the API key, to authenticate requests.

2.Data Retrieval:
Used requests.Session() to establish a session and sent a GET request to the API endpoint.
Parsed the response into a Python dictionary using json.loads().

3.Error Handling:
Implemented try-except blocks to handle potential errors, such as connection issues or timeouts.

4.Data Appending:
Extracted relevant fields from the API response (e.g., cryptocurrency name, price, market cap).
Appended the data to an existing dataset, ensuring proper alignment of fields.

5.Output:
Saved the updated dataset as a CSV file for further analysis or reporting.

6.Outcome:
Automated and repeatable process for fetching cryptocurrency data and maintaining an up-to-date dataset.
