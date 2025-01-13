# MULTIAGENT: Finance Advisor

The **MultiAgent Finance Advisor** is a Streamlit-based application that leverages a team of AI agents to process user queries. The agents are powered by the Groq model (LLaMA 3.3 70B) and are equipped with tools like DuckDuckGo for web search and YFinanceTools for financial data retrieval. The application allows users to input queries, such as summarizing analyst recommendations or fetching the latest news for a specific stock, and displays the results in a user-friendly format.

---

## Features

- **Web Agent**: Fetches and summarizes the latest news from the web using DuckDuckGo.
- **Finance Agent**: Retrieves financial data such as stock prices, analyst recommendations, and company information using YFinanceTools.
- **Agent Team**: Combines the capabilities of the Web Agent and Finance Agent to provide comprehensive responses to user queries.
- **Streamlit Interface**: A simple and interactive web interface for users to input queries and view results.
![image](https://github.com/user-attachments/assets/6ad75e7d-9848-47ae-934f-843fe9758147)
![image](https://github.com/user-attachments/assets/abce119a-8fe7-46b4-a1b4-314afa67e7b8)

---
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MushafMughal/MultiAgent-Finance-Advisor.git
   cd agent-team-query-processor
   ```
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```
3. Set up your environment variables:
    - Create a .env file in the root directory.
    - Add your API keys and other necessary configurations to the .env file.

4. Run the Streamlit app:
```bash
streamlit run app.py
```
---

## Usage

1. Open the Streamlit app in your browser.
2. Enter your query in the input box (e.g., "Summarize analyst recommendations and share the latest news for NVDA").
3. Click the "Submit" button to process the query.
4. View the results, which may include tables, summaries, and sources.

---

## Code Structure

- `app.py`: The main Streamlit application script.
- `README.md`: This file, providing an overview of the project.
- `.env`: Environment variables file for storing API keys and configurations.
- `requirements.txt`: List of Python dependencies.

---

## Dependencies

- `phi`: For creating and managing AI agents.
- `streamlit`: For building the web interface.
- `python-dotenv`: For loading environment variables.
- `duckduckgo-search`: For web search functionality.
- `yfinance`: For financial data retrieval.

---

## Example Queries

- "Summarize analyst recommendations for NVDA."
- "What is the latest news about Tesla?"
- "Get the stock price and company info for Apple."

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
