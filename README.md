# AI-CHATBOT-WITH-NLP

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: THUMMURU AKSHITHA

*INTERN ID*: CT06WR252

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION OF AI-CHATBOT-WITH-NLP*:

This Python program is a simple yet effective chatbot designed to respond to user inputs using both direct question-answer matching and basic intent recognition. It uses the Natural Language Toolkit (**nltk**) library to perform tokenization and lemmatization, helping the bot better understand the variations in user inputs. The program begins by downloading necessary NLTK resources like "punkt" for tokenizing sentences into words and "wordnet" for lemmatization, ensuring the chatbot can handle words in their root forms. A **WordNetLemmatizer** instance is created to simplify words into their base forms, which improves the chatbot’s ability to recognize user intents accurately.

The chatbot has two main layers of response handling. First, it checks if the user's input exactly matches any pre-defined questions stored in a **custom_qna** dictionary. These direct matches provide very specific, human-like responses to questions such as "who are you," "who made you," and "what can you do." This customization makes the chatbot feel more personal and engaging. If no direct match is found, the bot falls back to **intent-based replies**, which are structured around categories like greetings, goodbyes, and expressions of gratitude. Each intent contains a set of **keywords** and a list of possible **randomized responses**. For example, if a user says "hello" or "hi," the bot recognizes the **greeting** intent and responds with a randomly chosen friendly message such as "Hey!" or "Nice to see you!"

The text processing function **tokenize()** is responsible for breaking down the user's input into individual words, converting them to lowercase, and lemmatizing them. This way, similar words like "running," "ran," and "runs" are all interpreted as "run," making intent detection more reliable. The **get_intent()** function uses these tokens to determine which intent the user’s input matches by checking if any of the keywords appear. If none of the keywords match, the function returns a "default" intent, prompting a generic but encouraging response like "Tell me more!" or "Interesting... go on." Finally, the **get_response()** function manages the overall conversation flow by first attempting a direct lookup and, if unsuccessful, falling back to intent-based matching. Random selection from available responses ensures that the chatbot's replies feel varied and less repetitive, making conversations seem more natural.

Overall, this chatbot program demonstrates key concepts of natural language processing and basic artificial intelligence. It is lightweight, easy to extend with more questions, intents, and responses, and serves as a perfect project for beginners learning about text analysis, user interaction, and how to build intelligent applications in Python. By combining direct question-answer pairs with keyword-driven intent recognition, it strikes a nice balance between simplicity and functionality. With further enhancements, such as adding more intents, handling typos, or integrating a machine learning model, this chatbot could evolve into a much more advanced conversational assistant. As it stands, it’s a charming, customizable, and educational example of building a text-based chatbot from scratch.

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/c282364a-f302-4c18-a615-0447f65945b3)
