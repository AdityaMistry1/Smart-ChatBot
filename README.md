# Smart-ChatBot
Service chatbot made with NLP and cosine algorithm and no datasets
SmartBot - ML-Based Customer Service Chatbot
--------------------------------------------

Description:
This chatbot uses a simple machine learning model (Naive Bayes with TF-IDF) to respond to common customer queries.
It's built for local environments like Pydroid 3 and includes a confidence threshold to avoid guessing on unclear inputs.

Features:
- Understands questions about hours, returns, refunds, payments, orders, and more
- ML-based: Trained on labeled intent data
- Runs offline with scikit-learn
- Avoids incorrect answers by using a confidence threshold

How to Run (on Android with Pydroid 3):
1. Open this project in Pydroid 3 or copy SmartBot_Final.py.
2. Install scikit-learn if not already installed:
   pip install scikit-learn
3. Run the script.
4. Type any question like:
   - when are you open?
   - how do I return a product?
   - how can I pay?
5. Type 'bye' to exit.

Author: Mistry Aditya
