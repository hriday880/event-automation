# Event Report Document Generator

This Streamlit web application helps club secretaries automatically generate perfectly formatted Event Report documents (including inserting photos) without messing up the formatting.

## Features
- Provides an easy-to-use form for event details.
- Automatically inserts and scales uploaded photos into the document.
- Generates a downloadable `.docx` file formatted exactly to the required standard.

## Running Locally

1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the app:
   ```bash
   streamlit run app.py
   ```

## Deploying to Streamlit Community Cloud (For your Secretary)

Since this app no longer requires direct Google Drive integration, deploying it is incredibly easy:
1. Push this code to a **GitHub repository**.
2. Go to [share.streamlit.io](https://share.streamlit.io/) and log in with GitHub.
3. Click **New app** and select your repository, branch, and `app.py` as the Main file path.
4. Click **Deploy!** 

Now, you can simply give the Streamlit URL to your secretary. After every event, they can visit the site, fill in the form, and download the finished report document. They will then manually upload it to the correct Google Drive folder and update the tracker spreadsheet.
