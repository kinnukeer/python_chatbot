# python_chatbot
responses={
    "hi":"hello!",
    "how are you":"I'm just a computer program,but I'm functioning well."
    "what's your name":"I'm a chatbot,you can call me chatbot.",
    "bye":" Goodbye! feel free to return if you have more questions.",
}
#function to get a reponses from the chatbot
def get_response(user_input):
  user_input=user_input.lower()
  #check if the user input matches any predefined responses
  if user_input in responses:
    return responses[user_input]
  else:
    return "I'm sorry, "
