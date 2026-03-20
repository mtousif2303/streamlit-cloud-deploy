# Streamlit App Deployment

A Streamlit application deployed on Streamlit Cloud via GitHub CI/CD.

## Deployment Steps

1. **Build** your Streamlit application locally
2. **Setup** a Cloud account on [Streamlit Cloud](https://streamlit.io/cloud)
3. **Push** your code to this GitHub repository
4. **Connect** your GitHub repo to your Streamlit Cloud account
5. **Deploy** your application on Streamlit Cloud

## Project Structure

```
streamlit-app-deployment/
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy on Streamlit Cloud

1. Go to [share.streamlit.io](https://share.streamlit.io)
2. Click **New app**
3. Select this GitHub repository
4. Set the main file path to `app.py`
5. Click **Deploy!**
