# FashionSearch AI

## Overview

FashionSearch AI is an intelligent query response system designed to provide detailed and user-friendly answers to fashion-related queries. This project leverages a combination of search and generation layers to enhance the user experience by delivering informative and contextually relevant results. 

## Features

- **Search Layer**: Retrieves relevant fashion items from a dataset using keyword matching or predefined criteria.
- **Generation Layer**: Uses advanced AI models like GPT-3.5 to generate detailed, context-aware responses in natural language.
- **Versatile Query Handling**: Capable of answering a wide range of queries, including preferences for color, style, occasion, and more.

## Objectives

The primary goal of FashionSearch AI is to assist users in finding fashion items that align with their preferences by:
1. Enhancing the relevance of search results.
2. Generating comprehensible and engaging responses.
3. Improving overall user interaction and satisfaction.

## Implementation Details

### Data Preprocessing
- Cleaned the dataset by removing unnecessary columns, standardizing formats, and replacing blank entries.
- Removed HTML tags and extra characters to improve data quality.

### AI Integration
- Integrated GPT-3.5 for generating contextually relevant, natural language responses.
- Enabled dual-layer query processing to combine efficient data retrieval with enriched output.

### Query Response Generation
- **Search Layer**: Retrieves relevant items from the dataset.
- **Generation Layer**: Generates detailed and context-sensitive responses to user queries.

## Sample Queries
1. **Query**: "An orange summer dress or kurta to wear over blue denim jeans."
   - *Search Layer Output*: [Search-based response]
   - *Generation Layer Output*: [AI-generated detailed response]

2. **Query**: "Office wear sarees in elegant colors like pink, violet, or green with full embroidery for formal events."
   - *Search Layer Output*: [Search-based response]
   - *Generation Layer Output*: [AI-generated detailed response]

3. **Query**: "A versatile black leather jacket, suitable for various occasions, preferably in size XL."
   - *Search Layer Output*: [Search-based response]
   - *Generation Layer Output*: [AI-generated detailed response]

## Challenges Faced
- **Metadata Processing**: Issues in metadata processing affected display quality but were resolved with debugging.
- **Dataset Chunking**: Memory constraints limited dataset processing, though chunking was avoided due to dataset size.

## Lessons Learned
- Data preprocessing is essential for improving data quality.
- Advanced AI models significantly enhance the ability to provide meaningful and tailored responses.
- Efficient handling of large datasets is critical for scalability.

## Future Scope
- Implement as a Flask web application for better user interaction and aesthetics.
- Introduce criteria-based filters and interactive sessions.
- Explore additional optimizations for dataset processing and query handling.

## Conclusion
FashionSearch AI effectively combines the search and generation layers to deliver comprehensive and engaging responses. While the search layer retrieves relevant results efficiently, the generation layer adds context and depth, making it an invaluable tool for fashion-related queries.
