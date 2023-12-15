# Retail Store Database Assistant

![image](https://github.com/shaadclt/Retail-Store-Database-Assistant/assets/98437584/b540ea25-0829-4660-b249-4f077f4e32c9)

This project is a Retail Store Database Assistant that uses LangChain and Google Palm Language Model to interact with a MySQL database. Users can ask questions about the database, and the assistant will generate MySQL queries to retrieve relevant information.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- MySQL database
- [LangChain](https://github.com/langchain/langchain) library
- [Streamlit](https://streamlit.io/) for the web application

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/shaadclt/Retail-Store-Database-Assistant.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up your MySQL database and update the connection details in the code.

4. Create a `.env` file and add your Google API key:

    ```
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. Run the Streamlit application:

    ```bash
    streamlit run main.py
    ```

2. Enter your questions in the provided input field.

3. The application will interact with the MySQL database and provide answers.

## Configuration

- Modify `langchain_helper.py` and other relevant files to adjust configurations and database details.

## Contributing

If you would like to contribute to this project, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- [LangChain](https://github.com/langchain/langchain)
- [Google Palm Language Model](https://github.com/google-research/google-palm)

## Contact

For issues and inquiries, please contact [Mohamed Shaad](https://imshaad.in/).

---

**Made with ❤️ by Mohamed Shaad**
