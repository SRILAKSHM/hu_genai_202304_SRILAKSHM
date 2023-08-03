# SQL Query Generation using LLMs

The aim of this assignment is to develop a Generative AI application using Large
Language Models (LLM) that can generate SQL Queries. The user provides the intent of the
query by providing text based prompts. The LLMs should be able to produce the SQL Query.
The user should be able to provide context to the LLM by providing the table structure in a
structured and/or unstructured format.

## Table of Contents

- [Installation](#installation)
- [Examples](#examples)
- [Changelog](#changelog)
- [Authors and Acknowledgments](#authors-and-acknowledgments)
- [Contact](#contact)
- [FAQ](#faq)

## Installation

Instructions on how to install and set up the project:
•	Clone the repo – git clone /hu_genai_202304_SRILAKSHM
•	Install below libraries in your local
1.	os
2.	openai
3.	Langchain
4.	Json
5.	ConversationChain
6.	Logging
6.	tabulate

## Examples

•	To Select all data in the table – 
1.	User Input: Hi.. Can you help me
2.	User Input: SQL Queries
3.	Enter table name: Testing
4.	Enter column names separated by space: Name Rec
5.	Enter the number of rows in the table: 2
6.	Row1 : Enter values separated by space: Sri 3
7.	Row2: Enter values separated by space: Lakshmi 4
8.	Please enter the SQL query you want: SQL Query to get all data in table
o/p: SELECT * FROM Testing
•	When wrong question given – 
1.	User Input: Hi.. Can you help me
2.	Can you please rephrase the sentence to understand your query better.

## Authors and Acknowledments
•	Srilakshmi Vinnakota

## Contact

For questions, feedback or support, please contact:
•	Email: vinnakotasrilakshmirjy@gmail.com

## FAQ

Frequently asked questions and their answers:
•	Q1: What does this Project do?
  •	A1: It gives output for SQL Query of given table and requirement
•	Q2: What if I’m getting No module found error?
  •	A2: Install particular library using ‘pip install library_name’
