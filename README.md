# Adaptive Content Rating System using AI

An intelligent web content rating system that evaluates websites based on sentiment analysis, fake news probability, clickbait potential, and NSFW content detection.

## Features

- **Website Recommendations**: Get relevant website suggestions for your search queries
- **Content Analysis**: Evaluate web content for sentiment, fake news potential, clickbait, and NSFW content
- **Safe Search**: Automatic filtering of NSFW search queries
- **User Dashboard**: Track your search history and content analysis results
- **AI-Powered Chat Assistant**: Get information about the system and content ratings

## Technologies Used

- **Backend**: Python, Flask
- **API Integration**: OpenRouter API with DeepSeek and Mixtral models
- **Data Processing**: JSON for caching responses
- **Frontend**: HTML, CSS, JavaScript (Templates)

## Setup and Installation

1. Clone the repository
```
git clone https://github.com/krishnakanth6143/Adaptive-Content-Rating-System-using-AI.git
```

2. Install dependencies
```
pip install flask openai
```

3. Set your OpenRouter API key in app.py
```python
openai.api_key = "your_api_key_here"
```

4. Run the application
```
python app.py
```

5. Access the application at `http://localhost:5000`

## Project Structure

- `app.py`: Main Flask application with all routes and logic
- `templates/`: HTML templates for the web interface
  - `home.html`: Landing page
  - `index.html`: Search page
  - `dashboard.html`: User dashboard
  - `about.html`: About page
  - `faq.html`: Frequently asked questions
  - `trends.html`: Content trends
