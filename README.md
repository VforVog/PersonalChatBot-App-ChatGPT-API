Personal Virtual Assistant Using ChatGpt API -> Just make sure to drop your Pdf file!

You upload either a pdf or txt file.  
 
You write down the information that you want to provide. 

Here it is! 
Using the API of Chatgpt now you have your own personal assistant that can reply to questions based on your data!
Can be implemented as a chatbot in your website as well!

Enjoy:)

Installation
Install Langchain and other required packages.

pip install langchain openai chromadb tiktoken unstructured
Modify constants.py.default to use your own OpenAI API key, and rename it to constants.py.

Place your own data into data/data.txt.

Example usage
Test reading data/data.txt file.

> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
Test reading data/cat.pdf file.

> python chatgpt.py "what is my cat's name"
Your cat's name is Muffy.
