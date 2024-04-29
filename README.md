# 📍 Customized Chatbot for Frieren: Beyond Journey's End

![image](https://frieren-anime.jp/wp-content/themes/frieren_2023/assets/img/top/top/3_visual.jpg)

## ☞ Objective

This project aims to create a customized chatbot capable of answering questions about `"Frieren: Beyond Journey's End"` a Japanese manga series. 
The chatbot utilizes a specialized dataset containing character names from the series to provide accurate and relevant responses.

1. **Dataset Selection and Scenario Explanation**
   
   We selected a dataset comprising character names from "Frieren: Beyond Journey's End" to develop a chatbot that serves as an expert on the series. This dataset enables the chatbot to answer questions about the characters accurately.
2. **Dataset Preparation**

   The dataset was structured into a pandas DataFrame, with each character name represented as an individual entry. Embeddings were generated for each character name using the OpenAI API and stored in a CSV file.
3. **Performing Custom Queries**

   Custom queries were executed using the OpenAI API, allowing the chatbot to retrieve relevant information from the dataset based on user queries.
4. **Demonstrating Custom Performance**

   The chatbot's performance was evaluated through three queries, each with and without context. Results demonstrated the chatbot's ability to leverage contextual information for more accurate responses.

## ☞ Conclusions

The customized chatbot effectively responds to questions about "Frieren: Beyond Journey's End" characters, leveraging contextual information from the specialized dataset. By incorporating context, the chatbot delivers more accurate and relevant answers, enhancing the user experience.
