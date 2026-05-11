```markdown
# LLMs: From Text to Vector Space - An Interactive Demo

## Project Overview

This Google Colab notebook provides an interactive demonstration of how Large Language Models (LLMs), specifically BERT, process textual information. It visualises the journey of words from raw text into numerical representations (tokens and embeddings) and explores their semantic relationships within a high-dimensional vector space.

### Key Concepts Demonstrated:

1.  **Tokenisation**: Understanding how raw text is broken down into subword units (tokens).
2.  **Word Embeddings**: Converting tokens into dense, high-dimensional numerical vectors that capture semantic meaning.
3.  **Cosine Similarity**: Measuring the semantic relatedness between words by calculating the cosine of the angle between their embedding vectors.
4.  **Vector Space Visualisation**: Reducing high-dimensional embeddings to 2D and 3D using Principal Component Analysis (PCA) to visually explore how semantically similar words cluster together.

## Installation

To run this notebook, you need to install the necessary Python libraries. All required packages are listed and installed in the first code cell of the notebook.

```python
!pip install transformers torch scikit-learn matplotlib seaborn plotly -q
```

## Usage

1.  **Open the Notebook**: Access the `LLMs_Text_to_Vector_Space.ipynb` file in Google Colab.
2.  **Run All Cells**: Execute the cells sequentially, from top to bottom. You can do this by selecting `Runtime > Run all` from the Colab menu.
3.  **Interactive Exploration**: 
    *   Observe the tokenisation process for various words and phrases.
    *   Review the cosine similarity matrix to see numerical relationships between words.
    *   Interact with the 3D visualisation (Step 6) to rotate and zoom through the word embedding space.
    *   Use the interactive widget in Step 8 to compare your own chosen words and see their semantic similarities.

## Dependencies

*   `numpy`
*   `transformers` (Hugging Face)
*   `torch`
*   `scikit-learn`
*   `matplotlib`
*   `seaborn`
*   `plotly`
*   `ipywidgets`

## Model Used

The demo utilises the `bert-base-uncased` pre-trained model and tokeniser from the Hugging Face Transformers library.

## License

This project is open-source and available under the MIT License.

```
