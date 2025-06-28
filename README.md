# Columbia University Summer Programming Course Materials
Repository containing coursework materials from my Columbia University summer programming course, focusing on Python programming, data analysis, and natural language processing (NLP) fundamentals.

## Key Features
- Core Python programming concepts
- Practical NLP preprocessing workflows
- Pandas data manipulation techniques
- Clean notebook organization with commented code
- Real-world data analysis examples

## Repository Contents

### 📓 Jupyter Notebooks
1. **notebook.ipynb**  
   - Python fundamentals (variables, data types, operators)
   - String/list operations and lambda functions
   - Dictionary creation with `zip()`
   - Basic module imports

2. **pre-processing.ipynb**  
   - NLP text preprocessing techniques
   - Tokenization with NLTK
   - Stopword removal
   - Stemming using SnowballStemmer

3. **RP Data scientist.ipynb**  
   - Advanced DataFrame manipulation
   - Data filtering and selection
   - Financial data analysis case study

4. **TFP.ipynb**  
   - Basic data loading with Pandas

### 🐍 Python Scripts
- **TFP.py**  
  - Demonstrates Excel data loading with Pandas

## Technical Stack
- **Python 3.8**
- Core Libraries:
  - Pandas (data manipulation)
  - NumPy (numerical operations)
  - NLTK (natural language processing)
- Jupyter Notebook environment

## Getting Started

### Prerequisites
- Python 3.6+
- Jupyter Notebook
- Required packages: `pandas numpy nltk`

### Installation
```bash
# Clone repository
git clone https://github.com/<trbhmn2>/Columbia-Notebook.git

# Install dependencies
pip install pandas numpy nltk jupyter

# Download NLTK data
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"
