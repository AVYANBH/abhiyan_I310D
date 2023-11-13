# Data Bias | Abhiyan Bhandari

This project explores whether adjusting the severity threshold of the Perspective bias model can effectively distinguish between headlines with varying emotional intensity. Amidst the ongoing global humanitarian crisis, news coverage has been heavily focused on relevant topics. By setting the severity threshold to "Gravest" for headlines involving severe violence and "Serious" for other news, this project aims to identify potential patterns in the classification of headlines based on their emotional impact.

## Hypothesis
Based on the current global context, I **hypothesized** that headlines classified as "Gravest" will primarily relate to the ongoing Israeli-Palestinian conflict, while headlines categorized as "Serious" will represent a broader range of news topics.

### Perspective API
I am using the Perspective API code to run through the moderation machine learning model to find the toxicity scores of the News Headlines that were on Googles trending chart. The Perspective API's toxicity tool is a useful tool for identifying and flagging potentially toxic content. It is used in a variety of applications, like social media moderation, online forums, and other digital interactions. To evaluate the toxicity levels of trending news headlines, I used the Perspective API.

## Impementation
The initial step involved importing the necessary libraries to run the API's operation. Then, a unique API key from Google Cloud was utilized to establish a connection between the API and the project. The codebase provided in the assignment instructions served as the foundation for this analysis. I made modifications to enable the incorporation of the dataset into the model via a CSV file. Additionally, I also added a code to generate a new file containing both the headlines and their corresponding toxicity scores. Finally I also added code categorize the toxicity scores into a column in the new file that contained both the headline text and toxicity scores.

## Results
The implementation of this approach resulted in a comprehensive analysis of the toxicity levels within trending news headlines. The resulting insights can be leveraged to inform strategies for content moderation and promote a more conducive online environment.

The hypothesis that headlines classified as "Gravest" would primarily relate to the Israeli-Palestinian conflict, while headlines categorized as "Serious" would represent a broader range of news topics, was confirmed by the analysis. This observation highlights the effectiveness of the Perspective bias model in distinguishing between headlines with varying emotional intensity, particularly in the context of a global humanitarian crisis.

## Takeaways
News networks increasingly employ emotionally charged headlines to capture attention and drive engagement, resulting in a spectrum of headlines that evoke a range of intense emotions. This strategy aims to capitalize on human psychology, as people are more likely to click on headlines that trigger strong emotional responses, such as fear, sadness, anger, or curiosity. While this approach may generate clicks, it also contributes to a heightened emotional state among readers, potentially exacerbating existing anxieties or polarizing opinions.
