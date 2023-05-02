# NLP-Sentiment-Analysis

The objective of this project is dual. First, you will learn how to deal with a specific case of sentiment analysis (emotions) considering a conversational context. Second, you will learn to manipulate and design a model considering the final task.

### Project :

We have multiple **conversations**. 

In each **conversation**, there are **utterances** (textual content). 

Each **utterance**'s text is made of multiple **tokens** (word/punctuation/etc.).

This means our data will have the following structure:
- Dataset
  - Conversation
    - Utterance
      - Tokens

We want to **predict the emotion of each utterance**. Which means only utterances have a label:
- Dataset
  - Conversation
    - Utterance [ one of these labels: 🙂 😞 😠 😯 😐 🤮 😱 ]
      - Tokens
