# Pregnancy-Chatbot-with-language-translation-facility
An intelligent chatbot for pregnant women that offers personalized medical advice and information. It is well equipped with language translation facility to ensure accessibility across diverse linguistic demographics.
The basic requirements for building a chatbot are - 
- an env file having all the secret keys used.
- Requirements are already mentioned in requirements.txt
- Virtual environment is necessary for running the environment of chatbot.
- Frontend requires basic HTML,CSS and JavaScript.
- Backend is done using python.
- The knowledgebase is completely done by us , extracting various informations of pregnancy from authentic websites and books in a excel file.
- Gemini API is used for better and updated informations. It checks the knowledge base and extracts the appropriate response for the users and ensures that the chatbot might not respond to any other contents other than pregnancy as the chatbot is specially taliored for pregnant women.
- Gemini 1.5 Flash version is used its fastest multimodal model with great performance for diverse tasks. Flash models have one million token context window by default, which means we can process one hour of video, 11 hours of audio , codebases with more than 30,000 lines of codes.
- For translation we have used google translator API . Users can both command and get responses according to their prefered language.
- All Indian languages are applicable in the chatbot.
- FUTURE SCOPE - Adding more languages such that that chatbot can be used across all linguistic demographics of World.
- Integrate this chatbot to a pregnancy tailored website and then deploying it using Docker or any other advanced and suitable technology.
- Complexities faced - Use of OpenAI API instead of Gemini.
- Use of deep translator instead of google translator.    
