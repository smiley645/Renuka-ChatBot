# 🤖 Renuka Chatbot

Renuka Chatbot is a prototype AI chatbot built using **OpenAI, LangChain, Gradio, and Hugging Face**.  
It was developed during the **NxtWave Workshop**.

## ⚠️ Status: Prototype (Not Working Yet)
This chatbot currently **does not work** because I don’t have access to a working API key by default.  
If you have an API key, you can add it directly in the code.

## 🔗 Live Preview (UI Only)
[🚀 Check Out Renuka Chatbot Here](http://renukachatbot1.ccbp.tech)

## 🛠 Technologies Used
- OpenAI
- LangChain
- Gradio
- Hugging Face

## 🔧 How to Run (If You Have an API Key)
1.Install the required dependencies:
  pip install openai langchain gradio huggingface_hub

2.Embed your API key: Open your Python code file (e.g., chatbot.py) and locate the following line:
    openai.api_key = "your_api_key_here"
Replace "your_api_key_here" with your actual OpenAI API key.

3.Run the chatbot:
python chatbot.py

📌 Notes
This is a prototype created during the NxtWave Workshop.
The chatbot interface is visible, but it won't provide responses without a valid API key.
For better security in production, it's recommended to use environment variables to store your API key instead of embedding it directly in the code.



