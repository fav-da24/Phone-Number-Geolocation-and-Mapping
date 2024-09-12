# Phone Number Geolocation and Mapping

This Python project takes a phone number with a country code, determines the location and service provider associated with that number, and generates a map showing the location. The map is saved as an HTML file using the Folium library.

## Features

- Parse and validate phone numbers.
- Retrieve geographical location and service provider information.
- Use OpenCage Geocoding to get latitude and longitude.
- Generate an HTML map with Folium to visualize the location.

## Prerequisites

- Python 3.x
- Required Python packages

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/fav-da24/Phone-Number-Geolocation-and-Mapping.git
   cd phone-number-geolocation
   ```

2. **Set up a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   You need to install the following Python packages:

   ```bash
   pip install phonenumbers folium opencage
   ```

   Note: You may also need to install additional dependencies if they are not included in the package list.

## Usage

1. **Run the Python script:**

   ```bash
   python geolocation.py
   ```

2. **Enter the phone number with the country code** when prompted.

3. **Check the generated map**:
   - After running the script, an HTML file named `Location.html` will be created in the project directory.
   - Open `Location.html` in a web browser to view the map with the location marked.

## Code Explanation

- **`phonenumbers`**: Parses and validates the phone number.
- **`geocoder`**: Provides location description based on the phone number.
- **`carrier`**: Retrieves the service provider name.
- **`OpenCageGeocode`**: Fetches latitude and longitude for the given location description.
- **`folium`**: Creates an interactive map and saves it as an HTML file.

## API Key

- **OpenCage API Key**: Replace `Key` with your own OpenCage API key to use the geocoding service. You can obtain a key by signing up on the [OpenCage Data website](https://opencagedata.com/).

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or support, please contact [fav.da24@gmail.com](mailto:fav.da24@gmail.com).
