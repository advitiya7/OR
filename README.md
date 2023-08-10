# Nearest Mental Health Facility Finder using OpenRouteService Distance Matrix API

This Python script calculates the nearest mental health facility from a given list of addresses in Washington DC using the OpenRouteService Distance Matrix API. It utilizes a distance origin matrix to efficiently calculate travel distances between addresses and mental health facilities.

## Prerequisites

- Python 3.x
- `requests` library: Install it using `pip install requests`

## Getting Started

1. Sign up for an API key from the [OpenRouteService website](https://openrouteservice.org/sign-up/) if you don't have one.
2. Clone this repository to your local machine.

## Usage

1. Open `nearest_mental_health_facility_finder.py` in a text editor.
2. Replace `'YOUR_API_KEY'` with your actual OpenRouteService API key.
3. Modify the `addresses` list to include the coordinates of the addresses you want to find the nearest mental health facility for.
4. Modify the `mental_health_facilities` list to include the coordinates of mental health facilities.
5. Run the script using the command: `python nearest_mental_health_facility_finder.py`

The script will calculate the mental health facility with the least travel distance from each address in the `addresses` list and display the results.

## Example

```python
# List of coordinates (latitude, longitude) for addresses in Washington DC
addresses = [
    (38.8977, -77.0365),  # Example address 1
    (38.9101, -77.0147),  # Example address 2
    # Add more addresses as needed
]

# List of coordinates (latitude, longitude) for mental health facilities
mental_health_facilities = [
    (38.8888, -77.0500),  # Example mental health facility 1
    (38.9255, -77.0320),  # Example mental health facility 2
    # Add more mental health facilities as needed
]

# API endpoint for OpenRouteService Distance Matrix API
api_endpoint = "https://api.openrouteservice.org/v2/matrix/driving-car"

# Your OpenRouteService API key
api_key = 'YOUR_API_KEY'
