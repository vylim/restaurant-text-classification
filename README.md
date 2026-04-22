# restaurant-text-classification

Instructions for running
1. Navigate into repo directory.
2. Download the Yelp dataset files from [here](https://business.yelp.com/data/resources/open-dataset/).
3. Put all JSON files into the repo's directory.
4. Create virtual environment by running `virtualenv venv` and `source venv/bin/activate`
5. Install packages by running `pip install -r requirements.txt`
6. Create a `.env` file in the repo root with your API key:
   ```
   API_KEY=your_api_key_here
   ```
   This file is listed in `.gitignore` and will never be committed.