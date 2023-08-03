# Build-LLama2-Chatbot

In this project, we will build a Llama 2 chatbot in Python using Streamlit for the frontend, while the LLM backend is handled through API calls to the Llama 2 model hosted on Replicate. You will see how we:

- Get a Replicate API token
- Set up the coding environment
- Build the app
- Set the API token
- Deploy the app

1) To get a Replicate API token:
- Go to [https://replicate.com/signin/](https://replicate.com/signin/)
- Sign in with your GitHub account.
- Proceed to the API tokens page and copy your API token.

2) To Set up the coding environment

You can decide to work in local or in the cloud using Streamlit.

To work in local, you have to install replicate and streamlit using: pip install streamlit replicate

If working in the cloud environment, just create a requirements.txt file and paste: streamlit and replicate

3) To build the App

You can use the code provided in the app.py file

4) Set the API Token

You can set the API token in secrets to allow users to use your replicate API or Set the API token in the app asking them to provide their own API

5) Deploy the App

You can deploy the App in the cloud in three steps:

- Create a GitHub repository for the app like what I did.
- In Streamlit Community Cloud, click on the New app button, then choose the repository, branch, and app file.
- Last step, click Deploy! and the app will be live!


