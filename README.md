# Restaurant-Text-Classification

Our restaurant text classification uses data taken both reviews and businesses statistics from the popular Yelp app. This application uses Jupyter Notebook and n-gram models to classify types of restaurant cuisines and the formality of restaurants. After extracting and finding those results, we look at our f1-score, recall, precision, and many more to understand each classification. Lastly, we created a zero-shot LLM classification to get cuisine types and formality based on the review text.

## Setup Instructions
1. Navigate into repo directory https://github.com/vylim/restaurant-text-classification.git and clone it.
2. Download the Yelp dataset files from [here](https://business.yelp.com/data/resources/open-dataset/).
3. Put all JSON files into the repo's directory.
4. Create virtual environment by running `virtualenv venv` and `source venv/bin/activate`
5. Install packages by running `pip install -r requirements.txt`
6. Create a `.env` file in the repo root with your API key:
   ```
   API_KEY=your_api_key_here
   ```
   This file is listed in `.gitignore` and will never be committed.
