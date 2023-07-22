# visual-qa-chatbot

## Description

This project involves solving a visual question answering (VQA) problem using a proposed dataset. The dataset comprises synthetic scenes, each depicting interactions between people and objects, along with corresponding questions that inquire about the image content. The ultimate objective is to provide the correct answer given an image and a question. The answers in the dataset belong to three distinct categories:

1. **'Yes/No' answers:** This category includes questions that can be answered with a simple 'yes' or 'no'. For example, questions like "Is there a dog in the image?" or "Is the sky blue?" fall into this category.

2. **'Counting' answers:** In this group, questions require counting objects or people in the image and providing a numeric answer ranging from 0 to 5. For instance, questions like "How many cars are there?" or "Count the number of apples" belong here.

3. **'Other' answers:** The 'other' category encompasses questions that demand answers of varied types, such as colors, locations, attributes, and so on. For example, questions like "What color is the house?" or "Where is the book placed?" are included in this category.

The VQA problem is a challenging task that requires combining computer vision techniques with natural language processing to comprehend the image content and derive accurate answers to a diverse set of questions.

## Dataset

The provided dataset contains synthetic scenes and corresponding questions with answers falling into the three aforementioned categories. To train an effective VQA model, it is essential to ensure diversity in the scenes, questions, and answers to achieve robustness and generalizability.
