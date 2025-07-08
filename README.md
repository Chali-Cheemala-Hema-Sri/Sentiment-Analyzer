⚖️ AI Legal Sentiment Analyzer

This project analyzes legal documents to determine sentiment — Positive, Negative, or Neutral. It helps law firms, compliance teams, and researchers quickly evaluate the tone and implications of legal texts like contracts, client feedback, and case summaries.

🎯 Project Goals

* Automate sentiment classification of legal text
* Generate summarized sentiment insights
* Reduce manual review time and improve legal document analysis

⚙️ Implementation

* Developed using Python in Google Colab
* User interface built with Gradio
* Uses foundation models like Mistral-7B and FLAN-T5 via OpenRouter
* Supports both single-paragraph input and bulk classification via CSV upload
* Stores historical predictions with timestamps for tracking

🚀 Key Features

* Analyze legal sentiment in real time
* Upload CSV files containing multiple legal paragraphs
* Download sentiment-tagged CSV results
* View previously analyzed entries with date and time
* Uses few-shot prompting for high accuracy in tone detection


🧪 Tools & Technologies

* Gradio for building the web interface
* Pandas for CSV processing
* Requests for API interaction
* OpenRouter API to access LLMs like Mistral and FLAN-T5
* IBM WatsonX Prompt Lab for few-shot prompt experimentation
* Python for data handling and orchestration


📁 Project Structure

* AI\_Legal\_Sentiment\_Analyzer.ipynb – Colab notebook with the full working app
* requirements.txt – Python package dependencies
* README.md – Project documentation

✅ How to Use

* Open the notebook in Google Colab
* Run all cells to initialize the app
* Paste legal text or upload a CSV file with a 'text' column
* View predicted sentiments and download the output
* Access past results in the history section

📄 Sample Output

* Input: A legal paragraph
* Output: Predicted sentiment tag (Positive / Negative / Neutral)

📦 Requirements

The project requires basic packages including:

* Gradio
* Pandas
* Requests

These can be installed using a standard package installer before launching the app.

📜 License

This project is licensed under the MIT License.

🙌 Acknowledgements

* OpenRouter.ai for enabling access to advanced language models
* IBM WatsonX for prompt prototyping
* Gradio for streamlining machine learning UI development
* Hugging Face community for open-source model inspiration

