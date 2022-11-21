                                       Chatbot using NLP and Neural Networks in Python
## libraries :

- matplotlib
  - pyplot
- json
- string
- random
- nltk
  - WordNetLemmatizer
- numpy
- tensorflow
  - keras
    - Sequential
    - layers
      - Dense
      - Dropout
      
### Packages to download :
- punkt
- wordnet
- omw-1.4

#### Steps :
In order to create our training data below steps to be followed:
- create a vocabulary of all the words used in the patterns
- create a list of the classes- tags of each intent
- create a list of all the patterns within the intents file
- create a list of all the associated tags to go with each patterns in the intents file
- loop through all the intents
- tokenize each pattern and append token to words, the patterns and the
- associated tag to their associated list
- lemmatize all the words in the vocab and convert them to lowercase
- sorting the vocab and classes in alphavetical order and taking the set to ensure no duplicates occur

<img width="750" alt="image" src="https://user-images.githubusercontent.com/85149334/203036423-80025c1e-8ed2-4eaf-b17a-624e28f33c7b.png">

- list for training data
- creating bag of words model
- then will select an appropriate message/response from the tag

<img width="402" alt="image" src="https://user-images.githubusercontent.com/85149334/203037134-0370b2fe-85a5-4bf4-93bc-bf4ec9590b15.png">

<img width="534" alt="image" src="https://user-images.githubusercontent.com/85149334/203037229-444638e9-c910-45e6-83ef-de6940a1ec3d.png">

<img width="649" alt="image" src="https://user-images.githubusercontent.com/85149334/203037318-0b39ec62-55b2-4d92-b378-1b9e3d305e7a.png">

- running the chatbot

<img width="105" alt="image" src="https://user-images.githubusercontent.com/85149334/203037452-16b7c4ab-6cff-4c0a-9650-55be3f4e32b2.png">
