# IRWA Final Project (2026) - Part 1: Text Processing and Exploratory Data Analysis

## Project Overview

This repository contains Part 1 of the Information Retrieval and Web Analytics (IRWA) Final Project (2026). The goal of this phase is to perform Text Processing and Exploratory Data Analysis (EDA) on a dataset of fashion products. This serves as the foundational step for building a custom Retrieval Augmented Generation (RAG) search engine.

In this part, we load the raw product dataset, handle missing values, and preprocess textual data (HTML unescaping, tokenization, stopword removal, and stemming). We also generate various EDA visualizations, including word counts, price/discount distributions, and word clouds for product titles and descriptions.

**GitHub Tag:** `IRWA-2026-part-1`

## Requirements

This project requires **Python 3** and the following libraries:

* `pandas`
* `numpy`
* `matplotlib`
* `nltk`
* `wordcloud`

## Project Structure

* `part1.ipynb`: The main Jupyter Notebook containing all the code for data loading, text preprocessing, and EDA.
* `data/`: Folder containing the dataset (e.g., `fashion_products_dataset.json`). *(Note: Ensure the dataset is placed here before running).*
* `README.md`: This instruction file.

## Setup and Installation

1. **Clone the repository:**

   ```bash
   git clone <your-github-repo-url>
   cd <your-github-repo-folder>
   ```
2. **Install the required dependencies:**
   You can install the necessary Python packages using pip:

   ```bash
   pip install pandas numpy matplotlib nltk wordcloud
   ```
3. **NLTK Data:**
   The code relies on the NLTK `stopwords` corpus. The notebook includes a cell to download this automatically (`nltk.download("stopwords")`), but ensure you have an active internet connection on your first run.

## How to Run the Code

Since this part of the project is entirely contained within a Jupyter Notebook, running the code is straightforward:

1. Launch Jupyter Notebook or Jupyter Lab from your terminal:
   ```bash
   jupyter notebook
   ```
2. Open the `part1.ipynb` file.
3. Verify that the dataset is correctly located at `data/fashion_products_dataset.json` relative to the notebook.
4. Select **Kernel > Restart & Run All** (or run the cells sequentially from top to bottom) to execute the data loading, text processing functions, and view the EDA plots and word clouds inline.

## AI Usage Acknowledgment

In accordance with the course's AI Usage Policy, we acknowledge the following use of AI tools in the development of this project submission:

* AI tools (such as ChatGPT) were used to assist in structuring this `README.md` file and formatting our documentation.
* AI was utilized as a brainstorming and debugging assistant during the development of the text preprocessing pipeline (e.g., refining the regular expressions and stemming logic).
All final code and explanations have been reviewed by the team.
