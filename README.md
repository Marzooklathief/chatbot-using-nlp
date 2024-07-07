## Description
This Python script implements a simple chatbot using NLTK (Natural Language Toolkit). The chatbot engages in conversation based on predefined patterns and responses. It uses regular expressions to match user inputs and generate appropriate replies.
## Features
- **Greeting**: Responds to common greetings like "hi", "hello", etc.
- **Introduction**: Acknowledges when users introduce themselves.
- **Personalization**: Provides information about its name and creator.
- **Mood**: Shares its current state ("how are you") with predefined responses.
- **Politeness**: Responds to apologies and well-wishes.
- **Interest**: Expresses enthusiasm for cricket when asked about sports.
- **Location and Weather**: Provides a fixed response about its location (Chennai, India) and responds to queries about rain.
- **Goodbye**: Recognizes when users want to end the conversation ("quit") and bids farewell.
## Usage
1. **Setup**:
   - Ensure Python is installed on your system.
   - Install NLTK library:
     ```
     pip install nltk
     ```
2. **Running the Bot**:
   - Run the script `chatbot.py`:
     ```
     python chatbot.py
     ```
3. **Interaction**:
   - Start typing lowercase English sentences to interact with the chatbot.
   - Use "quit" to end the conversation.
## Patterns and Responses

The chatbot uses predefined patterns and responses stored in the `pairs` list. Each pattern is a regular expression (`re` module) that captures user inputs, and responses are selected randomly from a list of possible answers.
## Example Interactions
- **User**: "Hello"
  - **Bot**: "Hey there"
- **User**: "My name is Alice"
  - **Bot**: "Hello Alice, How are you today?"
- **User**: "What sports do you like?"
  - **Bot**: "I'm a very big fan of Cricket"
## Notes

- This chatbot is a basic demonstration and can be expanded with more patterns and responses to cover a wider range of topics.
- Feel free to modify the `pairs` list to add new conversation patterns or responses based on your needs.
## Author

- Created by lathif using Python's NLTK library.

---

This README file provides a clear overview of what your chatbot does, how to run it, and what users can expect when interacting with it. Customize it further as per your specific requirements and enhancements to the chatbot.
