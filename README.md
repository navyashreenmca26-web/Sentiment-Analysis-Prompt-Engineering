Sentiment Analysis Using Prompt Engineering
1. Problem Statement

An online shopping company wants to analyze customer reviews automatically to understand customer satisfaction.

2. Objective

To classify customer reviews into three sentiment categories: Positive, Negative, and Neutral.

3. Designed Prompt

You are an intelligent AI-based sentiment analysis system for an online shopping company.

Your task is to read customer reviews and identify the overall sentiment expressed by the customer.

Classify each review into exactly ONE of the following categories:

Positive
Negative
Neutral
Classification Guidelines
Positive: The customer expresses happiness, satisfaction, or appreciation.
Negative: The customer expresses disappointment, dissatisfaction, or complaints.
Neutral: The customer provides information without expressing a clear positive or negative opinion.
Rules
Understand the meaning of the customer review.
Identify the overall sentiment.
Return exactly one category.
Do not provide explanations.
Do not include punctuation or additional text.

Customer Review: {Enter customer review here}

Output:

4. My Own Examples and Expected Outputs
Customer Review	Expected Output
I am very happy with my new laptop.	Positive
The shoes are comfortable and beautiful.	Positive
The seller provided excellent service.	Positive
The camera stopped working after two days.	Negative
I am disappointed with the poor packaging.	Negative
The product quality is very bad.	Negative
My order contains a blue shirt.	Neutral
The product was delivered on Monday.	Neutral
The package has three accessories.	Neutral
The phone looks stylish, but its battery drains quickly.	Negative
5. Testing the Prompt

Input:

The smartwatch looks stylish, but its battery drains very quickly.

Expected Output:

Negative

6. Conclusion

Prompt engineering helps automatically identify customer opinions and understand customer satisfaction. It helps online shopping companies improve their products and services.


OUTPUTS
Output Examples – Sentiment Analysis
S.No	Customer Review (Input)	Expected Output
1	I love this product. The quality is excellent.	Positive
2	The shoes are comfortable and beautiful.	Positive
3	The seller provided excellent service.	Positive
4	The camera stopped working after two days.	Negative
5	I am disappointed with the poor packaging.	Negative
6	The product quality is very poor.	Negative
7	My order contains a blue shirt.	Neutral
8	The product was delivered on Monday.	Neutral
9	The package has three accessories.	Neutral
10	The phone looks stylish, but the battery drains quickly.	Negative
Prompt Testing
S.No	Input	Output
1	I purchased a laptop yesterday. It works perfectly.	Positive
2	The product arrived late and was damaged.	Negative
3	My package contains two books.	Neutral
