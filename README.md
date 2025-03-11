# Weather Data Analysis

This project uses the OpenWeatherMap API to retrieve current weather data for a specified city. The script makes a request to the API, extracts relevant weather information (such as temperature, humidity, wind speed, and description), and displays the data in a Pandas DataFrame. It also provides basic data visualization for the weather data.

## Project Structure

The script performs the following tasks:

### 1. API Request and Data Retrieval
- Sends a request to the OpenWeatherMap API to get current weather data for a specified city.
- The response is parsed as JSON, and the relevant weather details (temperature, humidity, wind speed, description, city name, and country) are extracted.

### 2. Data Storage
- Stores the extracted data in a Pandas DataFrame for easy manipulation and display.

### 3. Data Visualization
- Displays the weather data in a bar plot (temperature).
- Includes a conceptual example of how to handle historical data and visualize trends (requires paid access for historical data in OpenWeatherMap API).

### 4. Error Handling
- Handles common errors such as request issues (e.g., connection issues, bad response codes) and data extraction issues from the API response.

## Requirements

To run this script, you will need the following Python libraries:
- `requests`
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using pip:

pip install requests pandas matplotlib seaborn

## Configuration

1. Set up an account on [OpenWeatherMap](https://openweathermap.org/) and get an API key.
2. Replace the `YOUR_API_KEY` placeholder in the script with your actual API key.
3. Replace the `CITY` variable with the city you want to query weather data for.

## Usage

Run the script to get the current weather data for the specified city:

python weather_data_analysis.py

### Output

- The script will display the current weather data (temperature, humidity, wind speed, and description) in the form of a Pandas DataFrame.
- A bar plot of the temperature for the specified city will also be shown.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
