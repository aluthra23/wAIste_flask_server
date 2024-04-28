## Overview

The Flask server in this repository serves as the backend API for the wAIste waste management application. It handles image processing and interacts with machine learning models to categorize waste items and detect garbage. The server facilitates communication between the frontend mobile app and the AI models, enabling real-time waste management recommendations for users.

## Features

- **API Endpoints:** Provides endpoints for image upload and inference.
- **Integration with AI Models:** Utilizes the Roboflow platform's inference SDK to integrate with machine learning models for waste categorization and garbage detection.
- **Efficient Communication:** Ensures seamless communication between the frontend mobile app and AI models, enabling quick and accurate waste management recommendations.

## Models

The Flask server integrates two distinct machine learning models for waste management:
1. **Garbage Detection Model (garbage_detection-wvzwv/9):** This model identifies the presence of garbage in an image and provides bounding boxes and confidence scores for detected garbage items.
2. **Waste Categorization Model (garbage-classification-3/2):** This model categorizes waste items into different classes such as biodegradable, cardboard, glass, metal, paper, and plastic, along with confidence scores for each prediction.

## Getting Started

To set up the wAIste Flask Server locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Configure the Flask server settings as needed.
4. Run the Flask server using `python main.py`.
5. The server will start running locally, and you can access the API endpoints.

## Links

- [wAIste Mobile App Repository](https://github.com/narainsriram2020/wAIste): GitHub repository for the wAIste mobile application.
- [Flask Server Repository](https://github.com/aluthra23/wAIste_flask_server): GitHub repository for the wAIste Flask server.
