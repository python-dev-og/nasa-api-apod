![Python Version](https://img.shields.io/badge/python-3.11-blue.svg)
![Streamlit Version](https://img.shields.io/badge/streamlit-1.29.0-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![NASA API](https://img.shields.io/badge/NASA-API-red.svg)


# NASA Astronomy Picture of the Day Viewer

## Overview
This Streamlit application fetches and displays the NASA Astronomy Picture of the Day (APOD) along with its title and an explanation. It utilizes the NASA APOD API to retrieve the data.

## Features
- Fetches the daily astronomy picture from NASA's APOD API.
- Displays the image along with its title.
- Provides an explanation of the image.

## Requirements
- Python 3
- Streamlit
- Requests

## Installation
To set up this project, follow these steps:
1. Clone the repository.
2. Install the required Python packages:

   ```bash
   pip install streamlit requests
   ```

## Usage
To run the application, execute the following command in the terminal:

```bash
streamlit run app.py
```

## API Key
The application uses a NASA API key. It's recommended to replace the API key in the code with your own API key, which you can obtain by signing up at [NASA API](https://api.nasa.gov/).

## Configuration
The application currently uses a default configuration with a set API key. You may modify the `api_key` variable in the code to use a different API key.

## Disclaimer
This project is for educational purposes and is not officially affiliated with NASA.

## Contributions
Contributions are welcome. Please submit a pull request or open an issue to suggest improvements or add new features.

## License
This project is open-source and available under the [MIT License](LICENSE).
