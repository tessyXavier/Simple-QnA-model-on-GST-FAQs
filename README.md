# Simple-QnA-model-on-GST-FAQs

Getting answer automatically is magic!! its real AI (remember, the Turing Test?)

This project is a Simple Question-Answer (atomic query) based chatbot framework. Uses similarity based on different vectorizers, to find the matching question then responds with its corresponding answer.

Application Scope:

<li>Huge demand to take care of mundane queries
<li>Scales (leverage, automation, passive)
<li>Not much work in vernacular chatbot (serve humanity)

Notes:

<li>This chatbot is based on category classification first and then to similarity within the selected category.
<li>Different than the popular open source chatbot framework, Rasa, where NLU is based on intent and entities, whereas dialog management is based on sequence/LSTM prediction.
<li>Conceptually it is similar to Microsoft's QnA Maker. But the big difference is that, if you get whole this whole github code-base, your models would be local. Nothing on Server. So better security especially for sensitive data chatbots like HR or Finance.

  
## Scripts:
* app.py: Chatbot UI built using Flask, using templates/*.html
* bankfaqs.py: Chatbot core logic as well as knowledge-base.
## Data:
* faqs: csv files containing questions and answers
* static and templates: Flask UI related files
