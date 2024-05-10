# MSCSLM (Mathematically Similarity Checked Small Language Model)

MSCSLM is an open-source project dedicated to research in Mathematically Similarity Checked Small Language Models. It contains three main components: Data, Similarity Algorithm, and Input/Output functionalities. The project is implemented in JavaScript for accessibility and ease of development.

## How it Works

### Working of MSCSLM

MSCSLM operates in the following steps:

1. **Data**: The project consists of three datasets: responses, ignore words, and spelling mistakes. 
    - *Responses*: Contains the main dataset of responses.
    - *Ignore Words*: Words to be ignored during comparison.
    - *Spelling Mistakes*: Words to be replaced for spelling correction or synonym handling.

2. **Input**: The user enters prompts in the chat box.

3. **Trimming**: The input undergoes preprocessing where characters are trimmed, ignore words are removed, and spelling mistakes are corrected or replaced.

4. **Similarity Checking**: Using a provided algorithm, the similarity between the preprocessed input and the responses dataset is checked, and a respective similarity score is assigned.

5. **Output**: The top 2 results with the highest similarity scores are displayed as output.

### Processing

The processing involves four steps:

1. **Input**: User enters a prompt in the chat box.
2. **Trimming**: The input is preprocessed to remove characters, ignore words, and correct spelling mistakes.
3. **Similarity Checking**: The similarity between the preprocessed input and responses dataset is computed using an algorithm.
4. **Output**: The top 2 results with the highest similarity scores are displayed as output.

### Features

- Chatbot: Provides conversational responses based on user input.
- Search Engine: Retrieves relevant information based on user queries.
- Spelling Correction: Corrects spelling mistakes in user input for better accuracy.
- Synonym Handling: Allows for synonyms in the responses dataset.

## Future Improvements

1. Enhanced Algorithms: Improve similarity checking algorithms for better accuracy and performance.
2. Natural Language Understanding: Incorporate NLU techniques to better understand user queries.
3. Dynamic Responses: Implement dynamic responses based on context and user history.
4. Multi-language Support: Extend the project to support multiple languages for broader accessibility.
5. User Feedback: Incorporate mechanisms for users to provide feedback and improve response quality.

## Contribution

Contributions to the MSCSLM project are welcome! Feel free to submit pull requests, report issues, or suggest enhancements.

## License

MSCSLM is released under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the project for both non-commercial and commercial purposes.

