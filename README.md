Riyadh Guide is a mobile application that combines a number of features. This file contains part of the code used to apply sentiment analysis.

● Sentiment analysis is the process of classifying the emotional intent of text. Generally,
the input to a sentiment classification model is a piece of text, and the output is the
probability that the sentiment expressed is positive, negative, or neutral. Typically, this
probability is based on either hand-generated features, word n-grams, TF-IDF features (term
frequency-inverse document frequency) is a statistical measure that evaluates how relevant a
word is to a document in a collection of documents, or using bag of words model. Sentiment
analysis is used to classify customer reviews on various online platforms like in our
application Riyadh guide we will use Sentiment analysis to classify people's reviews on the
quality of places, another use case is for niche applications like identifying signs of mental
illness in online comments.
● Bag Of Words
We have used bag-of-words to represent the words before feeding them in the
machine-learning model. A bag of words is a simple way to convert words into numbers that
the model can understand and learn from. The bag of words model considers the whole
document as a “bag” of words, rather than a sequence. We represent the document simply by
the frequency of each word.

Also we use a ChatGPT API in the Riyadh Guide 
● ChatGPT API
OpenAI's Chat GPT API is a revolutionary tool for building conversational AI. It uses
natural language processing (NLP) to understand and generate human-like responses, making
it perfect for building chatbots, virtual assistants, and other conversational applications. Chat
GPT API is a product of Open AI, a company specializing in AI research and development. Itis a cloud-based API that provides access to Open AI's advanced language models, including
GPT-3 and GPT-4. It allows developers to integrate natural language processing (NLP) capabilities into their applications.
In our application, we will use an AI Text generator using the gpt-3.5-turbo model on
the admin side to facilitate adding place functionality, especially in writing the description of
that place and the services that they provide. Since ChatGPT uses NLP it suits our need in
writing a description in Arabic, giving more than one suggestion, also we can benefit from it
in correcting grammar and choosing appropriate vocabulary, this provides the admin with a
great capability to add places efficiently without wasting time during thinking of the perfect
place description. ChatGPT uses the user input known as a prompt and then replays with the
response, the prompt consists of keywords and phrases meant to spark a reply. You feed
ChatGPT a question or instruction and it will respond as though in a conversation. As much
as the prompt is clear and specific the response will match your expectations.

- In the Add place form we provide the admin with a feature that he can use ChatGPT
functionality when trying to write a description of the place he will add, he has the option of
writing it by himself or using AI text generator to help him correcting grammar or
terminology or writing the full description. By clicking on the button 
"انشاء الوصف بالذكاء الاصطناعي"
the admin enters a clear prompt of what he needs then the Ai text generator will 
respond to his query.
