# Drip v2 - Travel Planner

## Project Description
Drip v2 is a user-friendly, personalized travel assistance web application, aimed at simplifying and enhancing the travel planning experience. Utilizing the power of the GPT language model for natural language processing, the app allows users to interact and describe their dream trips in a conversational manner. The app then uses this information to generate customized itineraries and recommend activities that cater to the user's preferences.

The app was built using Flask for the backend, React for the frontend, and Firebase’s Realtime Database and Cloud Functions components for managing user data and application logic. Google Places API serves as the main location-data source.

## Challenges
Some of the challenges encountered during this project include:

**Backend Functionality:** The backend system for trip generation occasionally failed to produce optimal trips. Further work is required to improve this aspect.

**GPT Response Structure:** The inability to change the response structure of GPT presented some issues. For instance, when the AI recommends a city, additional Named Entity Recognition (NER) had to be performed using Spacy to extract the city names. Similarly, during the trip editing stage, the backend assumes the GPT response will be a numbered list, complicating the extraction of recommendations.

## Learnings
This project was my first deep dive into frontend development. I got to learn and work with React and TypeScript, gaining valuable practical experience. The Material-UI (MUI) components particularly were a joy to work with, providing a flexible and effective way to create a responsive and user-friendly interface.

Drip v2 has benefited greatly from the integration of OpenAI's GPT model, which gave me a fantastic opportunity to familiarize myself more with the OpenAI API, learn how to use the Chat models, and even carry out Named Entity Recognition with spaCy!

Perhaps the most significant learning from this project has been on a personal level. Working on both the backend and frontend, I discovered the satisfaction of having control over the entire development process. This experience has made me consider the role of a full-stack developer for my future career, which is a realization I hadn't expected when embarking on this journey. I love the idea of understanding and creating an application end-to-end, and this project has been a wonderful catalyst for that discovery.

In summary, this journey with Drip v2 has been enlightening and transformative. The technical skills I've honed and the personal insights I've gained are invaluable and will surely guide my future career decisions.

## Suggestions to Contributors
- Authentication System: I am looking to add a secure authentication system to personalize the user experience further.
- Trip Generation Logic: I am considering a more profound integration of GPT to handle trip generation logic.
- Transportation and Timing: These are features that existed in the initial version of the app. I am looking to reincorporate them into the current version.
- Comprehensive Trip Details: Eventually, I aim to offer a more comprehensive travel plan including flights, hotels, and guided tours.
