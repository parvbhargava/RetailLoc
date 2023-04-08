# RetailLoc
The above code is a Python script that retrieves store data from the Unicorn Store website and writes it to a CSV file. The code is divided into two functions: get_store_data and `write_store_data_to_csv`.

The get_store_data function takes two arguments: city and state. It sends a POST request to the Unicorn Store website with the specified city and state as parameters. The function uses the requests library to send the request and includes headers and cookies in the request. The response from the website is in JSON format, so the function uses the json library to parse the response text and returns the data as a Python dictionary.

The write_store_data_to_csv function takes two arguments: data and filename. It writes the store data to a CSV file with the specified filename. The function uses the csv library to create a writer object and write the data to the file. The first row of the file is a header row that specifies the column names. The rest of the rows contain the store data, with one row for each store.

The last two lines of the code call these two functions to retrieve store data for New Delhi, Delhi and write it to a file named “store_data.csv”.
