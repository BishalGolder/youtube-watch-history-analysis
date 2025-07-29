"""
# YouTube Watch History Analysis

## Project Description  
This is a personal data analysis project exploring my YouTube watch history using Python, Pandas, Matplotlib, and Seaborn. The analysis uncovers watch patterns, top channels, video trends, and session behaviors.

> **Note:** This repository does **not** include any personal data files (`watch-history.json`) to protect privacy.


## How to Download Your YouTube Data

1. Go to [Google Takeout](https://takeout.google.com/).  
2. Deselect all and select only **YouTube and YouTube Music** data.  
3. Choose **All YouTube data included**, deselect all, and click **History**.  
4. Under **Multiple Formats**, scroll to the bottom and select the **History** dropdown to `JSON`.  
5. Download the exported archive when ready.  
6. Extract the `watch-history.json` file and place it inside a folder named `data/` in this project directory.

---

## How to Run This Project

### Option 1: Run Locally

- Install Python and the required libraries if not already installed:
   Run this on your terminal or bash:
   
    pip install pandas matplotlib seaborn

- Use Jupyter Notebook or any Python IDE (e.g., VSCode) to run `youtube_analysis.ipynb`.
- Place your YouTube data JSON file in the `data/` folder as described above.

### Option 2: Run on Google Colab

- Upload your data file to Colab manually or mount Google Drive.
- **Note:** Accessing files on your computer directly from Colab or other browser-based notebooks may cause issues due to sandboxing and permissions. Upload files explicitly when required.

---

## Main Features

1. Summary statistics on watch habits  
2. Visualizations of watch activity by hour, weekday, and over time  
3. Top channels and videos analysis  
4. Watch session pattern detection  
5. Simple prediction of busiest watch times

---

## Privacy & Data Disclaimer

This repository contains no personal YouTube data. Please export your own data from Google Takeout and analyze it locally. Avoid uploading personal data to public repositories.

---

## License

This project is open source — feel free to reuse and adapt!
"""
