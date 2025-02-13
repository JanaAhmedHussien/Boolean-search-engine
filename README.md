# Boolean Search Engine

## Description
This project implements a simple **Boolean Search Engine** to process Boolean queries on a collection of text documents. It demonstrates how to build an inverted index and use it to evaluate queries with **AND**, **OR**, and **NOT** operations. 

The search engine provides a framework for text-based information retrieval using Boolean logic.

---

## Features
1. **Document Preprocessing**:
   - Tokenizes text.
   - Converts text to lowercase.
   - Removes punctuation for consistent indexing.

2. **Inverted Index**:
   - Maps terms to the list of document IDs where they appear.
   - Allows for efficient Boolean query processing.

3. **Boolean Query Processing**:
   - Supports **AND**, **OR**, and **NOT** operations.
   - Processes queries as space-separated strings.
   - Returns the list of document IDs matching the query.

4. **Example Queries**:
   - `technology AND workplaces`
   - `environment AND NOT conservation`
   - `social media OR interpersonal relationships`
   - `health AND public AND NOT governments`

---

## Document Collection
| Document ID | Document Text                                                                                      |
|-------------|---------------------------------------------------------------------------------------------------|
| A           | The importance of education in society and its impact on economic growth                         |
| B           | The benefits of regular exercise for maintaining physical and mental health                      |
| C           | The role of technology in modern workplaces: Increasing productivity and efficiency              |
| D           | The influence of social media on interpersonal relationships and communication                   |
| E           | The significance of environmental conservation efforts for sustainable development                |
| F           | The challenges and opportunities of globalization in the 21st century                            |

---

## Prerequisites
- **Python 3.8+**


