
---

# Mood2Trip - Executing the Travel Recommendation System

This README will guide you through the process of setting up and running the project **Mood2Trip**, an intelligent, emotion-aware travel and accommodation planning system.

You need Python 3.10 or above to be installed beforehand.

## Step-by-Step Execution Instructions

### 1. Install Dependencies

Install the necessary packages by running:

```
pip install -r requirements.txt
```

Ensure the internet connection is active for API-based modules (Google Maps, Places, Booking.com).

### 2. Prepare APIs

Before running the pipeline:

* Generate API keys for:

  * Google Geocoding API
  * Google Places API
  * Booking.com API

### 3. Run the Complete Pipeline

To execute the pipeline for a mood-based travel plan, run the Jupyter Notebook file

The system will:
* Ask dynamic questions using Gemini API
* Perform sentiment analysis using VADER
* Map mood to destination
* Cluster attractions using K-Means
* Recommend optimal hotels using Skyline computation
* Generate a travel itinerary with suggested day-wise plans and hotel options

## Troubleshooting

* Make sure all dependencies are installed using the requirements file.
* Ensure valid API keys are used and internet connectivity is available.
* Verify that the dataset and geolocation data are correctly formatted.
* Run scripts in proper sequence without skipping required inputs.
* If clustering results are incorrect, validate coordinates and clustering parameters.

---
