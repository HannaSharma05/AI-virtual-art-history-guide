The AI Virtual Art History Guide is a full-stack conversational chatbot designed to make learning art history more interactive and accessible. The idea was to create a virtual guide that can answer users' questions about artists, paintings, art movements, historical periods, and artistic techniques using natural language.

The application is built using Flask as the backend framework, while HTML, CSS, and JavaScript were used to develop the frontend interface. The chatbot uses Google Gemini 1.5 Pro as its Large Language Model to generate contextual responses.

One of the important features implemented was multilingual support, allowing users to interact with the chatbot in multiple languages. Another feature was voice input, which was integrated using the Web Speech API, enabling users to ask questions through speech instead of typing.

To improve response quality while controlling API usage, a sliding-window conversation management technique was implemented. Instead of sending the entire conversation history to the model every time, only the most recent six messages were sent. This maintained enough context for meaningful responses while reducing API token consumption and improving response efficiency.

The chatbot also maintains conversation history on the client side using DOM-based data binding and localStorage, allowing users to revisit previous interactions even after refreshing the page.
