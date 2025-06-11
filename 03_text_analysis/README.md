# Text Analysis Workshop Materials

This folder contains the materials for the workshop on Computational Text
Analysis. It conains a set of files, outlined below:

* `sotu.tsv`: This is a tab-separated file containing the text corpus which you
  can use throughout the lab. It contains four columns, title, author, date, and
  the text.
* `NLP_Workshop.ipynb`: This is the first Jupyter Notebook that contains the
  basic text analysis exercises. It involves reading text, calculating TF-IDF
  scores, a topic model, and word embeddings.
* `AL_Workshop.ipynb`: This is the second Jupyter Notebook that contains code to
  perform Active Learning using a RoBERTa Large Language Model (LLM).
* `NLP_workshop.Rmd`: This is an RMarkdown file containing the same instructions
  as the first Jupyter Notebook, but implemented using R libraries. You can use
  them similarly to the Jupyter Notebook.
* `_solutions`-files: These files contain the full code including the solutions.
  Use them to guide yourself to implementing the correct code and seeing how the
  methods are implemented.


If you are new to Python, and would like to familiarise yourself with it, there are some really good tutorials for beginners already out there -- here are two you could take a look at
* [Python-Beginners-Guide](https://github.com/jamwine/Python-Beginners-Guide/blob/master/Learn%20Python%20in%20Jupyter%20Notebook.ipynb)
* [Learning Python 3](https://mybinder.org/v2/gist/kenjyco/69eeb503125035f21a9d/HEAD?filepath=learning-python3.ipynb) from [here](https://gist.github.com/kenjyco/69eeb503125035f21a9d). This one you can run directly in your browser without having to install anything.


## Quick Colab tutorial:

### Setup
* Go to https://colab.research.google.com/
* Click "File" > "Open notebook..."
* A dialog will appear, click the GitHub tab
* Paste the URL of this GitHub repo: https://github.com/IAS-LiU/SICSS-2025
* Press Enter, and you’ll see a list of notebooks from that repo
* Click the one you want to open from the `03_text_analysis` directory

### Install packages
In Colab, you need an exclamation mark "!" before your install command.
To install a package:
* Insert a new code cell using the button "+ Code" (top left)
* Write your pip command with an exclamation mark at the beginning (e.g., `!pip install evaluate`)
* Run the cell
