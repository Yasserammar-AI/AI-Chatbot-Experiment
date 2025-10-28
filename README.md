# AI-Chatbot-Experiment
Simple AI chatbot experiment in Python
# AI Chatbot Experiment

**Creator:** Yasser Ammar 
**Language:** Python 
**Description:** 
A simple AI chatbot experiment. The chatbot can greet the user, answer basic questions, and respond politely to inputs it doesn't understand. 
This project demonstrates my interest in AI and programming.
# AI Chatbot Experiment
# Creator: Yasser Ammar
# Simple chatbot to answer basic questions

print("Hello! I am your AI assistant. What's your name?")
name = input("Your name: ")
print(f"Nice to meet you, {name}!")

while True:
user_input = input("Ask me anything (type 'exit' to quit): ").lower()

if user_input == "exit":
print("Goodbye! Have a great day!")
break
elif "how are you" in user_input:
print("I am just a program, but I am functioning well!")
elif "your name" in user_input:
print("I am your friendly AI assistant.")
else:
print("Interesting! I am still learning how to answer that.")
