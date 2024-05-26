# DATA-354 RAG Project

## Preliminary Steps

1. **Clone the GitHub Repository:**
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```
     git clone https://github.com/ibrahimseloh/DATA-354_RAG_Project.git
     ```

   This will create a local copy of the repository on your machine.

## Guidelines for Scraping

1. **Open the Jupyter Notebook:**
   - Open the file `STEP1_Scraping.ipynb`.

2. **Run the Notebook:**
   - Execute each cell in the notebook sequentially to perform the scraping successfully.

### Important Note:
Due to changes in the Ecofin platform, running the Jupyter Notebook may result in changes to the contents of `articles.csv` due to updates in the platform's news.

## Guidelines for Chat Bot

1. **Open the Terminal:**
   - Open the terminal in your code editor.

2. **Create a New Environment:**
   ```
   python -m venv myenv
   ```

3. **Activate the Environment:**
   - On Windows:
     ```
     myenv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source myenv/bin/activate
     ```

4. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```

5. **Install Llama3:**
   ```
   ollama pull llama3
   ```

6. **Install Nomic Embed:**
   ```
   ollama pull nomic-embed.txt
   ```

7. **Run the Application:**
   ```
   python app.py
   ```

### Using the Chainlit Platform:
- On the Chainlit platform, upload the CSV file named `articles.csv`.
