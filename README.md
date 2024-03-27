# Customer Feedback Analysis using BERTopic - adidas Stores in Germany

## Business Case

### Objective

The primary objective of this project is to enhance the in-store experience and online presence of Adidas stores across Germany. By analyzing customer feedback from Google reviews, we aim to identify key themes and sentiments that reflect the customer's overall experience. These insights will enable targeted improvements, contributing to increased customer satisfaction and business growth.

## Solution Overview

This project uses BERTopic, an advanced topic modeling technique based on transformers, to analyze textual data from Google reviews of adidas stores in Germany. BERTopic allows for the efficient extraction of meaningful topics from large volumes of text, providing a deep understanding of customer feedback. Feel free to explore the four notebooks. The 04_results contains all the visualizations and discussion of results, while the previous three are the steps taken to generate those results. 

### Data Source

The dataset comprises Google Maps reviews for adidas stores across Germany. Textual feedback from customers is used to understand the public opinion on adidas stores.

### Methodology

1. **Data Preparation**: Preprocessing of Google reviews to ready the data for NLP analysis.
2. **Sentiment Analysis**: Classifying the reviews by sentiment using a Transformer model.
3. **Topic Modeling with BERTopic**: Application of BERTopic to identify prevalent themes in customer feedback.
4. **Naming Topics**: Using the Mixtral-8x7B model to generate human interpretable titles for each topic.
5. **Topics over Time**: Identifying trends in the popularity of topics over the years.

## Code Usage

This repository contains all the code needed to replicate the analysis. The process is documented in multiple Jupyter Notebooks, detailing the steps data preprocessing, sentiment analysis, topic clustering and finally all the results.

### Steps to Reproduce the Results:
1. **Environment**: Setup your environment by installing the packages from the requirements.txt file. Add your anyscale-api token to the .env file. 
2. **Dataset**: The dataset is available in the adidas_input folder. The data was scraped using Instant Data Scraper on Google Chrome.
3. **Data Preprocessing**: Run the preprocessing notebook to clean and organize the dataset.
4. **Sentiment Analysis**: Run the sentiment analysis notebook to estimate the sentiment for each review.
5. **Topic Modeling**: Execute the BERTopic modeling notebook to identify and analyze topics. Explore the visualizations generated in this notebook.

## Potential Applications

The insights derived from this analysis can guide strategic decisions to improve customer satisfaction. Identified topics can pinpoint specific areas of improvement, such as customer service, product variety, or store experience. These insights can inform targeted actions at the individual store level potentially enhancing the customer experience and contributing to adidas's business success.

## Analysis Results

### Key Findings

- Sentiment Analysis indicates that the *proportion of negative reviews has decreased* between 2022 and 2024
- Using the Topic Model shows us that the main topics of the reviews include *employee friendliness, discounts and bargains, size availability and dog policy*.
- The recently added *Dog Ban in Stores* in the Herzo Store has increased the dissatisfaction among regular customers.
- The competitor's store managment responds to consumer feedback on the Google Maps reviews, while adidas does not.
- Customers are raising their voices regarding *Deteriorating Quality and Limited Selection* in the stores.

## Implications for Adidas and Strategic Recommendations

Based on the analysis results, several strategic implications emerge for adidas. Addressing these can help improve customer satisfaction, brand loyalty, and ultimately, business performance

### Store Policies and Customer Satisfaction

-**Revisiting Store Policies**: The dissatisfaction stemming from the dog ban policy suggests a need to revisit this decision. Conducting a survey or social listening to gauge broader customer sentiment towards such policies can inform a more inclusive approach.

### Product Offerings and Quality

-**Quality Assurance**: Address concerns about deteriorating quality by reviewing and enhancing quality control measures. Ensuring product excellence is key to maintaining brand reputation.
-**Expanding Selection**: Consider expanding product ranges to address complaints about limited selection. Tailoring inventory to local preferences based on data analysis can enhance the in-store experience.

### Employee Training and Store Experience

-**Staff Training**: Enhance staff training programs focusing on customer service excellence. Friendly and helpful staff are pivotal in creating positive in-store experiences.
-**Discounts and Promotions**: Analyze feedback on discounts and bargains to develop more attractive promotion strategies that can drive store traffic and satisfaction.

### Competitive Strategy

-**Competitor Benchmarking**: Learning from competitors who actively engage with customer feedback online, adidas can develop a more responsive feedback mechanism. This could involve a dedicated team to manage online interactions, reflecting a commitment to customer care.
