Personal Virtual Assistant Using ChatGpt API -> Just make sure to drop your Pdf or Txt file!

## Theory
Using the API of Chatgpt now you have your own personal assistant that can reply to questions based on your data!
Can be implemented as a chatbot in your website as well!


## 🚀 Installation
Install Langchain and other required packages.

<pre> pip install langchain openai chromadb tiktoken unstructured </pre>


Modify constants.py.default to use your own OpenAI API key, and rename it to constants.py.

Place your own data into data/data.txt

## Example usage
Test reading data/data.txt file.

<pre> > python chatgpt.py "What are Stylianos interests"
Stylianos interests outside of work is traveling and doing calisthenics. </pre>



