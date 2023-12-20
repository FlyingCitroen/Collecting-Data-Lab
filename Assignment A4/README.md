# Collecting-Data-Assignment_A4
📁 The folder is the assignment of week5 in Collecting Data.

## Description
The corpus includes three short novels by Agatha Christie. From this, Agatha Christie's tendencies when it comes to writing ultra-short stories can be explored.

## Text Selection
Influenced by computer arithmetic and the volume of this assignment, only the three shortest works by Agatha Christie included in Project Gutenberg are selected here. Given the number and length of Agatha's works, this corpus is only a small representation of his diction and writing style.

## Data Collection
The original file of the novel was downloaded from the Project Gutenberg web site. I processed it using Pandas and SpaCy to be able to recognize it more quickly through code.
Project Gutenberg is a project to collect and archive public domain texts and is the source of this book. Find out more at their website. https://www.gutenberg.org/

## Annotations
To the original CSV I used the spaCy library to add Filename, Text, Doc, Tokens, Lemmas, POS, Proper_Nouns, Named_Entities, NE_Words.
### Annotated CSV Description
| Column Name     | Data Type     | Description                                      |
| --------------- | ------------- | ------------------------------------------------ |
| Filename        | Text          | Name of the file                                 |
| Text            | Text          | Content of the text                               |
| Doc             | Text          | Spacy document object                            |
| Tokens          | List          | List of tokenized words                           |
| Lemmas          | List          | List of normalized word forms (lemmatized forms)  |
| POS             | List          | Part-of-speech tags                               |
| Proper_Nouns    | List/Boolean  | Indicates whether it is a proper noun (Yes/No)    |
| Named_Entities  | List          | List of named entity recognition results          |
| NE_Words        | List          | List of words containing named entities           |



**AssignmentID:** Week5 Assignment A4


