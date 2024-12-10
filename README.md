# Implementation-of-Chatbot-using-NLP

<h2>Overview</h2>
The College Chatbot is a Python-based chatbot that utilizes machine learning algorithms and natural language processing (NLP) techniques to provide automated assistance to users with college-related inquiries. The chatbot aims to improve the user experience by delivering quick and accurate responses to their questions.

<h2>Features</h2>
<ul>
  <li>College admission related queries could be answered through it. </li>
   <li>Viewing user profiles and retrieves attendance and grade/ pointers.</li>
   <li>College students can get information about examinations to be held.</li>
   <li>College students can fetch particulars about placement activities. </li>
  <li>Understands various user intents such as greetings, farewells, gratitude, and more.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>Python</li>
   <li>NLTK</li>
   <li>Scikit-learnScikit-learn</li>
   <li>Streamlit </li>
  <li>JSON for intents data</li>
</ul>

<h2>Methodology</h2>
The chatbot is developed using a combination of natural language processing techniques and machine learning algorithms. The methodology involves data preparation, model training, and chatbot response generation. The data is preprocessed to remove noise and increase training examples using synonym replacement. Multiple classification models are trained and evaluated to find the best-performing one. The trained model is then used to predict the intent of user input, and a random response is selected from the corresponding intent's responses. The chatbot is devoloped as a web application using Flask, allowing users to interact with it in real-time but yet to be deployed.
