Personal Virtual Assistant Using ChatGpt API -> Just make sure to drop your Pdf file!

You upload either a pdf or txt file.  
 
You write down the information that you want to provide. 

Here it is! 
Using the API of Chatgpt now you have your own personal assistant that can reply to questions based on your data!
Can be implemented as a chatbot in your website as well!

Enjoy:)

<hr>

## 🚀 Installation
Install Langchain and other required packages.

<pre> ``` pip install langchain openai chromadb tiktoken unstructured ``` </pre>


Modify constants.py.default to use your own OpenAI API key, and rename it to constants.py.

Place your own data into data/data.txt.

Example usage
Test reading data/data.txt file.

> python chatgpt.py "What are Stylianos interests"
Stylianos interests outside of work is traveling and doing calisthenics.

