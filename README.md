Hotel Chatbot

Overview

This project is a Hotel Chatbot that integrates with the ChatGPT API to provide automated responses for hotel-related queries. The chatbot handles both predefined FAQs and dynamic AI-generated responses based on user input.

Features

Predefined Questions & Answers: The bot includes a database of frequently asked questions (FAQs) about the hotel, such as room availability, check-in/check-out times, amenities, and pricing.

AI-Powered Responses: If a user's query is not found in the predefined list, the chatbot will generate a response using the ChatGPT API.

Seamless User Experience: Users can ask any hotel-related question, and the chatbot will determine whether to provide a predefined response or generate one dynamically.

Fast and Efficient: Ensures quick responses by prioritizing predefined answers before making an API request.

How It Works

The user asks a question about the hotel.

The chatbot checks its predefined database for a matching question.

If a match is found, the bot replies instantly with the predefined answer.

If no match is found, the bot queries the ChatGPT API and returns an AI-generated response.

The conversation history is maintained for a seamless interaction experience.

Getting Started

Clone the repository:

git clone https://github.com/your-username/hotel-chatbot.git

Install dependencies:

npm install

Set up API keys:

Obtain an API key from OpenAI for ChatGPT access.

Store the key in an environment variable (e.g., .env file):

OPENAI_API_KEY=your_api_key_here

Run the chatbot:

npm start

Technologies Used

Backend: Node.js, Express

API: OpenAI's ChatGPT API

Database: MongoDB (for storing predefined FAQs)

Contribution

Contributions are welcome! Submit an issue or a pull request with improvements.

License

This project is licensed under the MIT License.
